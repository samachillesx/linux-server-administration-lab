# Linux Server Administration

## Overview 

I provisioned and administered an Ubuntu Linux server, implemented SSH-based remote administration, configured firewall rules, deployed an Nginx web server, managed system services, analyzed system logs, configured file permissions, and automated server health checks and backups using Bash and cron.

I configured the server for remote administration using SSH, secured using UFW firewall rules, and configured it to host a web application using Nginx. Also, I included a Bash automation for server health monitoring and server configuration backups using cron.

## Objectives

- Deploy and configure an Ubuntu Linux server
- Create and manage Linux users and groups
- Configure file ownership and permissions
- Configure SSH for remote administration
- Implement SSH key-based authentication
- Secure SSH access
- Configure UFW firewall rules
- Install and configure Nginx
- Manage Linux services using systemd
- Monitor processes and system resources
- Inspect system and application logs
- Perform basic network troubleshooting
- Automate server health checks using Bash
- Automate server configuration backups
- Schedule tasks using cron
- Document troubleshooting procedures

## Technologies

- Ubuntu Linux > Server operating system
- Bash > Automation and administration
- SSH > Remote server administration
- UFW > Firewall
- Nginx > Web server
- systemd > Service management
- Cron > Task scheduling
- Git > Version control
- HTTP > Web communication
- TCP/IP > Network communication
- DNS > Name resolution

## Architecture

## Architecture ```text Developer Machine | | SSH | Port 22 v +-----------------------+ | Ubuntu Server | | | | UFW Firewall | | / \ | | SSH HTTP | | 22 80 | | \ / | | \ / | | Nginx | | | | | Web Content | | | | Bash Automation | | ├── Health Check | | └── Backup | | | | systemd | | Services | +-----------------------+ | v Web Browser







