# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

This activity is about learning how containers work and how they are different from Virtual Machines. I used the KillerCoda playground to practice Docker commands and run an Nginx web server. I was also able to test the server using a local request and see the Nginx welcome page.

## Objectives

* Understand the difference between Virtual Machines and Containers.
* Use a Docker-enabled environment in KillerCoda.
* Practice basic Docker commands.
* Download and run an Nginx image.
* Check and manage a running container.
* Document the commands and results using Markdown.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name my-nginx nginx
curl http://localhost:8080
docker ps
docker stop my-nginx
docker ps
docker ps -a
docker rm my-nginx
```

## Skills Learned

I learned how to use Docker from the terminal and how a Docker image can be used to create a container. I also learned how to connect a host port to a container port using port mapping. Running the Nginx server helped me understand how a container can provide a working web service without setting up a full virtual machine.

## Challenges Encountered

One small challenge I had was understanding where to put the `-d` and `-p 8080:80` options. I accidentally entered them as separate commands, which gave me a command not found message. I realized that they should be included in the `docker run` command. After that, the Nginx container started successfully and the curl command showed the Nginx welcome page.
