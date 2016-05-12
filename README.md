### What's this?
A useful CLI to bash-in a docker image (by running a ad-hoc container) or a running container.

Generally you will need it when debugging a Dockerfile or inspecting the content of an image/container.
### Install
sudo sh install.sh
### Play
#### Bash-in an image
```
bash-in-docker -i <image_id>
```
#### Bash-in a container
```
bash-in-docker -c <container_id>
```
### Enjoy!