# docker-tools
Scripts I've written to handle certain docker tasks. As long as you're running docker, they should work fine.

## Installation
1. Download/clone this project
2. Run `chmod +x <FILE>` on whichever script you want to be able to execute
3. At this point, you can run any project by name (`./docker-clean`), as long as you point to their directory.
4. As another step, you can add each utility to your $PATH if you want to be able to run them anywhere.

## Scripts
### docker-clean
I had issues with `docker image prune` hanging on mac, so I wrote this. It removes all dangling images by default, but there are plenty of other options to change its behavior.
