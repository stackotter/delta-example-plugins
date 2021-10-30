# Example Plugins for Delta Client

This repository contains a few example plugins to help developers get a practical understanding of how to use the plugin API.

## Usage

```sh
# make sure that the version of delta client cloned supports plugins (not all branches might) (for now use the `plugins` branch).
sh setup.sh

# Enter the directory containing the example you want to try
cd HelloWorld

# Build the example and then run Delta Client with the built plugin installed
sh build-and-run.sh
```

## Example Plugins

### Hello world

Prints a message for all of its life-cycle events (such as getting loaded and unloaded). Prints a message when the player joins a server and when the player joins a world.
