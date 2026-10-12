# Laboratory 8: The Cloud Security Engineer

## Mission Overview

This activity is about securing an Ubuntu server using a firewall. I started an Nginx web application using Docker, tested it with curl, and configured UFW to control incoming network traffic.

## Objectives

* Understand the Principle of Least Privilege.
* Learn about the attack surface of a server.
* Configure UFW with a Default Deny policy.
* Allow SSH and port 8080.
* Document the commands and results in GitHub.

## Commands Executed

```bash
docker --version
docker run -d --name secure-web-app -p 8080:80 nginx
docker ps
curl http://localhost:8080
docker logs secure-web-app
sudo ufw status verbose
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

## Skills Learned

I learned how to run a web server using Docker and test it with curl. I also learned how to configure firewall rules and allow only the ports needed by the server. This activity helped me understand why server security is important in cloud computing.
