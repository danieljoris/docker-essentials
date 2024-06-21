# Docker Essentials

A comprehensive guide to the most important Docker commands, organized by category for easy reference. This repository is designed to help developers and administrators master Docker commands for their daily tasks and prepare for interviews at top tech companies.

## 📦 Volume

- `docker volume create`: Creates a new volume.
- `docker volume ls`: Lists all volumes.
- `docker kill`: Kills one or more containers.
- `docker volume rm`: Removes one or more volumes.

## 🌐 Network

- `docker network create`: Creates a new network.
- `docker network ls`: Lists all networks.
- `docker network rm`: Removes one or more networks.
- `docker network connect`: Connects a container to a network.
- `docker network disconnect`: Disconnects a container from a network.
- `docker network inspect`: Inspects one or more networks.

## 🗂️ Registry

- `docker login`: Logs in to a Docker registry.
- `docker logout`: Logs out from a Docker registry.
- `docker push`: Pushes an image to a registry.
- `docker pull`: Pulls an image from a registry.
- `docker search`: Searches for images in a registry.
- `docker tag`: Tags a local image with a new tag.

## 📋 Manage Containers

- `docker run`: Runs a new container.
- `docker start`: Starts one or more stopped containers.
- `docker stop`: Stops one or more running containers.
- `docker restart`: Restarts one or more containers.
- `docker exec`: Executes a command in a running container.
- `docker ps`: Lists containers.
- `docker logs`: Fetches logs of a container.
- `docker pause`: Pauses all processes within a container.
- `docker wait`: Blocks until a container stops, then prints the exit code.
- `docker export`: Exports a container's filesystem as a tar archive.
- `docker rename`: Renames a container.

## 🛠️ Service

- `docker service ls`: Lists services.
- `docker service ps`: Lists tasks of a service.
- `docker service create`: Creates a new service.
- `docker service update`: Updates a service.
- `docker service scale`: Scales a service.
- `docker service logs`: Fetches logs of a service.
- `docker stack services`: Lists services in a stack.

## 🖼️ Manage Images

- `docker image ls`: Lists images.
- `docker image rm`: Removes one or more images.
- `docker image build`: Builds an image from a Dockerfile.
- `docker image commit`: Creates a new image from a container's changes.
- `docker import`: Imports the contents from a tarball to create a filesystem.
- `docker history`: Shows the history of an image.

## 🧹 Clean Up

- `docker rm`: Removes one or more containers.
- `docker rmi`: Removes one or more images.
- `docker kill`: Kills one or more containers.
- `docker prune`: Removes all unused containers, networks, images, and volumes.

---

## Contributing

We welcome contributions to improve this repository! If you have suggestions for new commands, improvements to existing descriptions, or any other enhancements, please feel free to submit a pull request or open an issue. Your contributions will help make this guide more comprehensive and useful for the community.

### How to Contribute

1. **Fork the repository**: Click the "Fork" button at the top right of this page to create a copy of this repository on your GitHub account.
2. **Clone your fork**: Clone the forked repository to your local machine.
    ```bash
    git clone https://github.com/danieljoris/docker-essentials.git
    ```
3. **Create a new branch**: Create a new branch for your contribution.
    ```bash
    git checkout -b feature/your-feature-name
    ```
4. **Make your changes**: Make the necessary changes and commit them.
    ```bash
    git commit -m "Description of your changes"
    ```
5. **Push to your fork**: Push your changes to your forked repository.
    ```bash
    git push origin feature/your-feature-name
    ```
6. **Submit a pull request**: Go to the original repository and submit a pull request. Provide a clear description of your changes and why they should be merged.

---

This repository is designed to help developers and administrators master Docker commands for their daily tasks and prepare for interviews at top tech companies.

We appreciate your efforts to improve this guide!
