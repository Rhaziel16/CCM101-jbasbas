# Docker Compose Guide

## What does the services: block do?

The `services:` block defines the containers used in the application. In this file, it contains the database and Nextcloud services.

## How did the Nextcloud app container know how to find the database?

The Nextcloud container uses the `MYSQL_HOST` environment variable to find the database container. Its value is `database`, which is the name of the database service.

## What is the difference between docker run and docker-compose up -d?

The `docker run` command is used to run a container individually. The `docker-compose up -d` command uses the Compose file to deploy the required containers together in the background.
