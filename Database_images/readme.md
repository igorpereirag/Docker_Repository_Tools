#  Docker Repository
 
This repository serves as a simple guide to Docker, containing essential commands, tools, and popular container images that I use frequently.

## Docker: An Overview

### What is Docker?

Docker is an essential tool in modern software development, enabling the creation, deployment, and management of applications within containers. Containers package an application and its dependencies into a standardized unit for seamless deployment across different environments.

## Essential Docker Commands

### Pull

```bash
docker pull <image>
```

Downloads an image from Docker Hub to your local machine.

### Run

```bash
docker run <image>
```

Creates and runs a container from an image.

### PS

```bash
docker ps
```

Lists all running containers.

### Stop

```bash
docker stop <container ID>
```

Stops a running container.

### RM

```bash
docker rm <container ID>
```

Removes a container.

### Images

```bash
docker images
```

Lists all available images locally.

### RMI

```bash
docker rmi <image ID>
```

Removes a local image.

## Docker Tools

### Docker Compose

Docker Compose simplifies the process of defining and running multi-container Docker applications with a single YAML configuration file.

### Docker Swarm

Docker Swarm is a native Docker orchestration tool for deploying and managing container clusters.

### Kubernetes

Kubernetes is an open-source platform for automating the deployment, scaling, and operation of containerized applications.

## Popular Docker Hub Images

### NGINX

NGINX is a high-performance web server and reverse proxy.

- **Image**: `nginx`

### MySQL

MySQL is an open-source relational database management system.

- **Image**: `mysql`

### PostgreSQL

PostgreSQL is an open-source relational database management system.

- **Image**: `postgres`

### MongoDB

MongoDB is a NoSQL document-oriented database.

- **Image**: `mongo`

### Redis

Redis is an in-memory data structure store used as a database, cache, and message broker.

- **Image**: `redis`

## Example Usage

To run an NGINX container and map port 8080 on the host to port 80 on the container, you can use the following command:

```bash
docker run --name my-nginx -p 8080:80 -d nginx
```

This command creates a new container named "my-nginx", maps port 8080 on the host to port 80 on the container, and starts the container in the background using the NGINX image.

Feel free to explore and utilize the resources in this repository for your Docker-related projects and tasks. For further information, please refer to the official Docker documentation at [https://docs.docker.com](https://docs.docker.com).