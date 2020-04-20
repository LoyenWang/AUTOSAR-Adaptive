# The container with dev environment

The Dockerfile contains configuration of the container with development environment:

- C++20
- Python3
- Conan
- Meson
- Git

### Build image

In `tools/dev_env` use:

`docker build -t autosar-adaptive-dev .`

### Run container
`docker run -d -t --name <container_name> -v <path_to_repo:/home/dev/workspace> autosar-adaptive-dev`

i.e

`docker run -d -t --name autosar-adaptive-dev -v C:\AUTOSAR-Adaptive:/home/dev/workspace autosar-adaptive-dev`

### Credentials 
`dev:dev`

### Usage with VS Code

https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack