# Containerized Linux Services Management Using Docker

## Project Overview

This project demonstrates how Linux-based services can be containerized and managed using Docker and Docker Compose.

## Technologies Used

- Linux
- Docker
- Docker Compose
- Nginx
- MySQL
- Ubuntu
- Git & GitHub

## Services

- **Nginx** — Web server
- **MySQL** — Database service
- **Ubuntu** — Linux environment for administration and testing

## Docker Features Demonstrated

- Docker images and containers
- Container lifecycle management
- Port mapping
- Docker volumes
- Persistent MySQL storage
- Docker networks
- Container-to-container communication
- Environment variables
- Dockerfile
- Docker Compose
- Health checks
- Resource limits
- Docker security basics
- Git and GitHub

## Project Architecture

```text
                    Docker Compose
                         |
          +--------------+--------------+
          |              |              |
       Nginx           Ubuntu         MySQL
          |              |              |
       Port 8082      Testing/Admin    Database
                         |
                  Docker Network
                         |
                    mysql:3306
                         |
                    mysql-data
                       Volume