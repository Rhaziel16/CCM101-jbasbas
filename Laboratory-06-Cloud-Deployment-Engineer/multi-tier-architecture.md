# Multi-Tier Architecture

## What is Two-Tier Architecture?

A two-tier architecture separates an application into two parts: the web/application tier and the database tier. Each part has its own role and works together to run the application.

## The Web/Application Tier

The web/application tier handles the user interface and HTTP requests. In this activity, Nextcloud is used as the application tier.

## The Database Tier

The database tier stores the application's data, such as user accounts and file information. In this activity, MariaDB is used as the database.

## Why Separate Them?

Keeping the web application and database in separate containers makes them easier to manage. Each container can do its own job without putting both parts in one container.
