# Docker-Cheatsheet-repository
Docker is a popular platform used to develop, deploy, and run applications inside containers. Containers are lightweight, standalone, and executable packages that contain all the necessary software, libraries, and dependencies needed to run an application. Docker provides a way to package and distribute applications in a consistent and portable manner, regardless of the environment they are deployed in.

Key components of Docker include:

Images: Blueprints for containers, containing everything needed to run an app.

Containers: Lightweight, isolated environments running instances of Docker images.

Docker Engine: Core component for building, running, and managing containers.

Dockerfile: Instructions for building Docker images.

Docker Registry: Repository for storing and sharing Docker images.

Volumes: Mechanism for persisting and sharing data between containers and the host machine.

Networking: Allows containers to communicate with each other and the outside world.

Docker commands:

docker run<image_name>: Starts a new container from an image.

docker ps: Lists running containers.

docker stop <container_id>: Stops a running container.

docker rm <container_id>: Removes one or more containers.

docker images: Lists available images on your system.

docker pull<image_name>: Pulls an image from a registry.

docker build<path_to_Dockerfile>: Builds an image from a Dockerfile.

docker exec<container_id> <command>: Runs a command inside a running container.

docker logs<container_id>: Fetches the logs of a container.

docker-compose up: Manages multi-container applications defined in a Compose file.

docker kill $(docker ps -ql): kill most recent container.
