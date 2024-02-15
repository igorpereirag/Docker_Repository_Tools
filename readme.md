# Docker Repository

This repository serves as a simple guide to Docker, containing essential commands, tools, and popular container images.

## Docker: An Overview

### What is Docker?
Docker is an essential tool in modern software development, enabling the creation, deployment, and management of applications within containers. Containers package an application and its dependencies into a standardized unit for seamless deployment across different environments.

## Essential Docker Commands

- **Pull**: `docker pull <image>`
  - Downloads an image from Docker Hub to your local machine.

- **Run**: `docker run <image>`
  - Creates and runs a container from an image.

- **PS**: `docker ps`
  - Lists all running containers.

- **Stop**: `docker stop <container ID>`
  - Stops a running container.

- **RM**: `docker rm <container ID>`
  - Removes a container.

- **Images**: `docker images`
  - Lists all available images locally.

- **RMI**: `docker rmi <image ID>`
  - Removes a local image.

- **Inspect**: `docker inspect <container ID>`
  - Displays detailed information about a container.

- **Logs**: `docker logs <container ID>`
  - Displays the logs of a container.

- **Exec**: `docker exec -it <container ID> <command>`
  - Executes a command inside a running container.

## Docker Tools

- **Docker Compose**: 
  - Simplifies the process of defining and running multi-container Docker applications with a single YAML configuration file.

- **Docker Swarm**: 
  - A native Docker orchestration tool for deploying and managing container clusters.

- **Kubernetes**: 
  - An open-source platform for automating the deployment, scaling, and operation of containerized applications.

## Popular Docker Hub Images

- **NGINX**
  - A high-performance web server and reverse proxy.
  - Image: `nginx`

- **MySQL**
  - An open-source relational database management system.
  - Image: `mysql`

- **PostgreSQL**
  - An open-source relational database management system.
  - Image: `postgres`

- **MongoDB**
  - A NoSQL document-oriented database.
  - Image: `mongo`

- **Redis**
  - An in-memory data structure store used as a database, cache, and message broker.
  - Image: `redis`

## Example Usage

To run an NGINX container and map port 8080 on the host to port 80 on the container, you can use the following command:

```bash
docker run --name my-nginx -p 8080:80 -d nginx
```

This command creates a new container named "my-nginx", maps port 8080 on the host to port 80 on the container, and starts the container in the background using the NGINX image.

Feel free to explore and utilize the resources in this repository for your Docker-related projects and tasks. For further information, please refer to the official Docker documentation at [https://docs.docker.com](https://docs.docker.com).