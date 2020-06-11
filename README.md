# python-tools-docker

Docker images with the preinstalled python modules

| This repository is currently work-in-progress |
| --------------------------------------------- |

The images are based on the [Python images](https://hub.docker.com/_/python) available on the Docker Hub. Builds are automated by the Docker Hub and will also be executed if there is an update to the Python base image.

For now the images are based on the `slim` tags of the base image.

## Docker repositories

| Repository | Tags | Docker Pull Command |
| ---------- | ---- | ------------------- |
| [pytest](https://hub.docker.com/r/wumaxd/pytest) | `3.6-slim`, `3.6`, `3.7-slim`, `3.7`, `3.8-slim`, `3.8` | `docker pull wumaxd/pytest` |
| [pylint](https://hub.docker.com/r/wumaxd/pylint) | `3.6-slim`, `3.6`, `3.7-slim`, `3.7`, `3.8-slim`, `3.8` | `docker pull wumaxd/pylint` |
