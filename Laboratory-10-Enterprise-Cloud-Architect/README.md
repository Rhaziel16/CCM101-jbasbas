
# Mission 10: The Enterprise Cloud Architect

## 1. Mission Overview

In this mission, I set up a website using Ghost and MySQL with Docker on Ubuntu Server inside VirtualBox. I used Docker Compose to manage the containers. I also configured the firewall and created a backup script that runs automatically every day. The goal was to make the website work, protect its data, and restore data when needed.

## 2. Objectives

- Set up Ubuntu Server using VirtualBox.
- Install Docker and Docker Compose.
- Run Ghost and MySQL in connected containers.
- Use Docker volumes to keep database and website content.
- Configure UFW to block unnecessary incoming connections.
- Allow the required ports for SSH and the website.
- Create a Bash script for database backups.
- Schedule automatic backups using cron at 2:00 AM daily.
- Test the website, restore a backup, and check the system after rebooting.

## 3. Commands Executed

### Check System Resources

```bash
date
free -h
df -h /
```

### Connect to Ubuntu Server

```bash
ssh -p 2222 vin@127.0.0.1
```

### Deploy and Check Docker Containers

```bash
cd ~/cloudnova
docker compose pull
docker compose up -d
docker compose ps
```

### Check Firewall and Network Ports

```bash
sudo ufw status verbose
sudo ss -tulpn
```

### Run and Check the Backup Script

```bash
./automation-script.sh
ls -lh ~/backups
cat ~/backups/backup.log
```

### Check the Scheduled Backup

```bash
crontab -l
```

### Test the System After Reboot

```bash
sudo reboot
```

After reconnecting to the server, check the containers and firewall:

```bash
docker ps
sudo ufw status verbose
crontab -l
```

## 4. Skills Learned

In this activity, I learned how to:

- Set up and run a website using Docker.
- Connect Ghost to a MySQL database.
- Keep data safe using Docker volumes.
- Set up a firewall to limit access to the server.
- Create backups and restore deleted data.
- Schedule a backup script to run automatically.
- Check if the website and containers are still working after a restart.

This activity helped me understand how the different parts of a cloud system work together. I also learned that saving backups and checking the system are important to avoid losing data.
