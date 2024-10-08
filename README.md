# Docker Hierarchical Optimization Model Predictive Control

## Overview

Docker container for the [Hierarchical Optimization Model Predictive Control](https://github.com/ddebenedittis/hierarchical_optimization_mpc) repo.

The `build.bash` and the `run.bash` files are used to automatically build and run the image.


## Preliminaries

Install [Docker Community Edition](https://docs.docker.com/engine/install/ubuntu/) (ex Docker Engine) with post-installation steps for Linux.

Install [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#setting-up-nvidia-container-toolkit) (nvidia-docker2).


## Usage

Build the docker image with
```shell
./build.bash [-a] [-f] [-h] [-r]
```
With the following optinal arguments:
- `-a-`, `--all`: build the image with all the dependencies
- `-f`, `--ffmpeg`: build the image with ffmpeg (for saving videos)
- `h`, `--help`: show the help message
- `-r`, `--rebuild`: rebuild the image

Run the container with
```shell
./run.bash
```

This repo also supports VS Code devcontainers.


## Hierarchical Optimization Model Predictive Control

See the [README.md](src/README.md).


## Author

[Davide De Benedittis](https://github.com/ddebenedittis)