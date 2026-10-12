# Laboratory 09 - Cloud Automation Engineer

## Mission Overview

This mission focuses on using a Bash script to automate the backup of application data. It also uses Cron to schedule the backup to run automatically every day at 2:00 AM.

## Objectives

* Understand Bash scripts, variables, and Cron jobs.
* Create a script that compresses application data.
* Use `chmod +x` to allow script execution.
* Schedule an automatic backup using Cron.
* Document the process and provide screenshots as evidence.

## Commands Executed

```bash
mkdir -p app-data
echo "This is critical client data." > app-data/data.txt
cat /root/backup.sh
chmod +x /root/backup.sh
/root/backup.sh
ls -lh /root/backups/
tar -tzf /root/backups/*.tar.gz
crontab -l
env EDITOR=nano crontab -e
service cron status
```

## Skills Learned

I learned how to create and run a Bash script, manage file permissions, compress files, and schedule tasks using Cron. I also learned why backups and careful testing are important when managing cloud systems.
