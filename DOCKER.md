Docker Commands Cheat Sheet

1. Docker Basics

Command

Description

docker --version

Check Docker version installed

docker info

Display system-wide information about Docker

docker help

Get help with Docker commands

2. Working with Containers

Command

Description

docker run <image>

Run a container from an image

docker run -d <image>

Run a container in detached mode (background)

docker run --name <name> <image>

Run a container with a custom name

docker ps

List running containers

docker ps -a

List all containers (including stopped ones)

docker stop <container_id>

Stop a running container

docker start <container_id>

Start a stopped container

docker restart <container_id>

Restart a container

docker rm <container_id>

Remove a stopped container

docker logs <container_id>

View container logs

docker exec -it <container_id> bash

Access a running container via shell

3. Working with Images

Command

Description

docker images

List all available Docker images

docker pull <image>

Download an image from Docker Hub

docker build -t <image_name> .

Build an image from a Dockerfile

docker rmi <image_id>

Remove a Docker image

4. Docker Volumes and Networks

Command

Description

docker volume create <volume_name>

Create a volume

docker volume ls

List all volumes

docker network create <network_name>

Create a network

docker network ls

List all networks

5. Docker Compose

Command

Description

docker-compose up -d

Start containers in detached mode from a docker-compose.yml file

docker-compose down

Stop and remove containers defined in docker-compose.yml

docker-compose ps

List containers managed by Docker Compose

6. Docker System Cleanup

Command

Description

docker system prune

Remove unused containers, networks, and images

docker container prune

Remove stopped containers

docker image prune

Remove unused images

7. Other Useful Commands

Command

Description

docker inspect <container_id>

Get detailed information about a container

docker stats

Display real-time resource usage of running containers

docker top <container_id>

Show running processes inside a container
