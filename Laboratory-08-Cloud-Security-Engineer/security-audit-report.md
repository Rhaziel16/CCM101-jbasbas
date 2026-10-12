# Security Audit Report

## 1. Principle of Least Privilege (PoLP)

The Principle of Least Privilege means giving users only the access they need to do their tasks. It helps protect cloud accounts because users cannot access resources without permission.

## 2. Attack Surface

An attack surface refers to the possible entry points that attackers can use to access a server. Open ports, running services, and exposed applications can increase the risk of attacks.

## 3. Default Deny Policy

A Default Deny policy blocks incoming traffic unless a firewall rule allows it. This is safer because only approved connections can reach the server instead of allowing all connections.

## 4. Security Audit

The web application was deployed using Docker and tested using curl. The server firewall was then configured to block incoming traffic by default while allowing SSH and TCP port 8080. The firewall status and rules were checked during the activity.

## 5. Evidence

Screenshots of the terminal results are saved in the screenshots folder.
