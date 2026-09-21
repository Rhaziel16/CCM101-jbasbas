# MinIO Deployment

## Environment

I used KillerCoda with Ubuntu 24.04 to deploy MinIO. Docker was already available in the environment.

First, I checked the Docker version:

    docker --version

The result showed:

    Docker version 29.1.3

I also checked if there were running containers:

    docker ps

## First Problem

I first tried to pull the MinIO image using:

    docker pull minio/minio

However, it did not work. KillerCoda returned a pull access denied error:

    pull access denied for minio/minio

Because of this problem, I used the MinIO image from Quay instead.

## Successful MinIO Image

I ran:

    docker pull quay.io/minio/minio

The image was downloaded successfully.

## MinIO Docker Command

I then started the MinIO container using:

    docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
    -e "MINIO_ROOT_USER=cloudadmin" \
    -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
    quay.io/minio/minio server /data --console-address ":9001"

## Checking the Container

I used:

    docker ps

The result showed that the `minio-server` container was running.

The ports used were:

- Port 9000 - MinIO API
- Port 9001 - MinIO Web Console

I also checked the logs using:

    docker logs minio-server

The logs showed that the MinIO Object Storage Server and WebUI were running.

## Environment Variables

### MINIO_ROOT_USER

The value was:

    cloudadmin

This is the username used to log in to the MinIO Web Console.

### MINIO_ROOT_PASSWORD

The value was:

    CloudNova2026!

This is the password used to log in to the MinIO Web Console.

## MinIO Web Console

I accessed the MinIO Web Console using port:

    9001

I logged in using:

    Username: cloudadmin
    Password: CloudNova2026!

## Bucket Created

I created a bucket named:

    client-photos

I then uploaded:

    sample.txt

The file was successfully shown inside the `client-photos` bucket.

## Problem With Port 9001

At one point, I typed:

    9001

directly in the terminal.

The terminal returned:

    9001: command not found

I learned that `9001` is a port number, not a Linux command. I used the KillerCoda port access option to open the MinIO Web Console instead.
