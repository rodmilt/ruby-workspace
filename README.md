# A Ruby workspace using a dev container

This repository is a Ruby workspace supported by a cross-platform Docker-based dev container. The header (`.h`) files should be placed under the `include/` folder, while the implementation (`.cpp`) files should be placed under the `src/` folder.

## Requirements

This repository requires the following one-time setup:

- Install the [Docker desktop application](https://www.docker.com/products/docker-desktop/). You don't need to do anything with Docker other than installing it on your operating system.
- Install [Visual Studio Code](https://code.visualstudio.com).
- Open Visual Studio Code and install the Dev Containers extension.

Having done that, download or clone this repository into your local machine and open its folder in Visual Studio Code. If you see a popup with an option to "Reopen in Container," click that. Otherwise, click on the Dev Containers icon at the bottom left corner and select "Reopen in Container." You can also type F1 to launch VSCode's Command Palette and search for and select "Dev Containers: Reopen in Container." This will reopen this repository in the dev container where all development environment tools (compiler, linker, debugger, etc.) are available.

## Running Ruby 

To make sure Ruby is installed, run the command:

```
ruby -v
```

To run interactive Ruby:

```
irb
```

RubyOnRails (Rails for short) is also installed, and you create a Rails application by running the following command from the main folder of this workspace:

```
rails new APP_NAME_GOES_HERE
```

Check out [The Rails Commandline](https://guides.rubyonrails.org/command_line.html) guite for more options.