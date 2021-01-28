# docker-interactive-setup

Bunch of scripts to be run in interactive docker containers for a more confortable experience and to handle repetitive tasks (updates, etc...) for you.

## How to use

Go in the directory for your distribution, click on `setup.cli` and then the "Raw" button. Copy the whole content of the file and paste it in your newly created interactive container. It will run all commands in the container shell to set it up neatly.

## Current features

- Pretty prompt: Color and date for better readability of big scrollbacks

- System update: to not have to do it all yourself each time you start a container.

- History: Bigger history (10000 lines, should be <1MB even maxxed out) and better handling of history (save history to history file for each command run instead of when leaving the shell) so that e.g. tmux sessions have the full history instead of an empty one.
