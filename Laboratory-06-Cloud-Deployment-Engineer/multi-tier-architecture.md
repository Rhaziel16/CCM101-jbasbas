# Multi-Tier Architecture

## What is Two-Tier Architecture?

A two-tier architecture separates an application into two main parts: the web/application tier and the database tier. Each part has its own job and works together to provide the application.

## Web/Application Tier

The web/application tier handles the user interface and receives HTTP requests from users. In this activity, Nextcloud serves as the application tier.

## Database Tier

The database tier stores important information such as user accounts and application data. In this activity, MariaDB is used as the database.

## Why Separate Them?

Separating the web application and database makes the system easier to manage and maintain. If they are in separate containers, each part can be updated or managed without putting everything in one container.
