# DNR-Editor-Dockerfile
Dockerfile to run a Distributed NodeRED instance. Ideal for testing with other NodeRED docker containers.


To run perform this command in the same directory as the Dockerfile:
```
docker build --network=host -t dnr-editor:1.0 .
```
Tested on Ubuntu 18.04. Assumes docker is already installed.

Distributed NodeRED: https://github.com/namgk/dnr-editor
