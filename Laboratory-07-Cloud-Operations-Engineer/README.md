# Laboratory 07 - Cloud Operations Engineer

## Mission Overview

In this laboratory, I worked as a Cloud Operations Engineer. I checked the condition of a Linux server, deployed an Nginx web server using Docker, generated web requests, and checked the logs and resource usage of the container. The goal was to use actual system information to see if the server and application were working properly.

## Objectives

* Check the server's RAM and disk storage.
* Monitor the running processes and CPU load.
* Deploy an Nginx web server container.
* Generate normal web requests and an error request.
* Check application logs using Docker.
* Monitor the container's CPU and memory usage.
* Document the results using Markdown.

## Monitoring Commands Executed

```bash
free -h
df -h /
top
docker run -d --name client-website -p 8080:80 nginx
docker ps
curl http://localhost:8080
curl http://localhost:8080/hidden-admin-page
docker logs client-website
docker stats
```

## Skills Learned

I learned how to check the basic condition of a Linux server using command-line tools. I also learned how to deploy an Nginx container, create test web requests, find errors through Docker logs, and monitor the resources being used by a container.
