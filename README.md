# WebSSH Docker
This Docker image allows you to run a WebSSH server on an Alpine Linux system out of the box.

Supports the x86_64, ARMv7 and ARMv8a (ARM64) architectures out of the box.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need Docker installed on your system.

### Installing and Running

You can clone this repository and build the Docker image.

```
$ docker build -t webssh-docker .
```

OR, you can pull the Docker image from my repository on Docker Hub!

```
docker pull darktohka/webssh-docker
```

### Running the image

You will need to expose one port in order to communicate with the WebSSH server.

```
docker run -d -p 8080:8080 darktohka/webssh-docker
```