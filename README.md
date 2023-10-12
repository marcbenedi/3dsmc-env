# 3D Scanning & Motion Capture (IN2354) - Development Environment

Docker image with all the required dependencies for the lecture https://niessner.github.io/3DScanning/


## Install Docker (and `docker-compose` or `docker compose`)

The first step is installing docker: https://docs.docker.com/engine/install/

## Build the development image

The following command will take some time. It will create a Docker image and install and compile the required dependencies.

```bash
docker build . -t 3dsmc
```

## Start the development environment

```bash
docker-compose up

# Or
# docker compose up
```

### Access the environment

In the web browser open the following link: http://localhost:8443/

Alternatively, you can access the CLI of the environment by executing: `docker exec -it 3dsmc /bin/bash`





