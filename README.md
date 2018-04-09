# docker-cheat

- docker image for cheat: [weshigbee/cheat](https://hub.docker.com/r/weshigbee/cheat)
- `cheat` (<https://github.com/chrisallenlane/cheat>) is a command that shows examples of commands, similar to `tldr`

# usage:

```bash

alias cheat='docker run --rm -it weshigbee/cheat'

cheat cheat
cheat ls

cheat --help
cheat --list
cheat --search <keyword>
cheat --directories

```