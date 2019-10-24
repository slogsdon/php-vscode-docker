# php-vscode-docker

> Demo of Visual Studio Code's remote development features using containers

## Requirements

- [Docker](https://www.docker.com)
- [Visual Studio Code](https://code.visualstudio.com)
- [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

## Getting Started

Search for and select the below in Visual Studio Code's Command Pallette (i.e. `Cmd-Shift-P` or `Ctrl-Shift-P`):

```
> Remote-Containers: Open Folder in Container...
```

In the open folder dialog, open this project's directory. Visual Studio Code will open a new window and proceed to:

- Setup and start a Docker container
- Setup and configure a Visual Studio Code Server installation
- Install defined Visual Studio Code extensions

At this point, you'll have a working development environment without the need to have things locally installed.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
