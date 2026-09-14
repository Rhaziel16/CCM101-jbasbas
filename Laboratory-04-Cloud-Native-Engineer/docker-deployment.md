# Docker Deployment

## Docker Commands

### 1. Check Docker Version

```bash
docker --version
```

This command checks the Docker version installed in the KillerCoda environment.

### 2. Check Docker Information

```bash
docker info
```

This command shows information about the Docker environment.

### 3. Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the Nginx image from Docker Hub.

### 4. Run the Nginx Container

```bash
docker run -d -p 8080:80 --name my-nginx nginx
```

This command creates and runs an Nginx container in the background and connects port 8080 of the host to port 80 of the container.

### 5. Test the Nginx Server

```bash
curl http://localhost:8080
```

This command sends a request to the Nginx server and displays its HTML response.

## Container Lifecycle

### 6. List Running Containers

```bash
docker ps
```

This command shows the containers that are currently running.

### 7. Stop the Nginx Container

```bash
docker stop my-nginx
```

This command stops the running Nginx container.

### 8. Verify the Container Status

```bash
docker ps
```

This command checks the running containers and confirms whether the Nginx container is still running.

### 9. Show All Containers

```bash
docker ps -a
```

This command shows both running and stopped containers.

### 10. Remove the Container

```bash
docker rm my-nginx
```

This command removes the stopped Nginx container.
