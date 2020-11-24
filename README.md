# Docker Commands

- `docker build . : build the image`

- `docker ps : lists all the running containers`

- `docker run -p 3000:80 e9775276737e : run the container with the image name on the end(we need to expose the port 3000 in order to run it in the browser).`

- `docker stop container_name : used to stop the running container(container_name: use docker ps to get the list of running containers)`

- ` docker ps -a: lists all the containers built on your system`

- ` docker ps --help: lists all the command options with docker ps`

- ` docker start/restart container_name: to restart an already existing container`

`Fun Fact: we can run the same container multiple times simultaneously by just changing the port no in case it requires a local server.`

- `docker run -p 3000:80 -d e9775276737e: to run the container in detached mode i.e terminal wont be locked after you run   the container.`

- `docker attach container_name : to attach a detached running conatiner`

- `docker logs container_name : shows the logs of a detached container which is not currently running`

- `docker logs -f container_name : to keep the terminal attached and keep it listening to the logs for the container      which is not currently running`

- `docker start -a conatiner: to start a container already attached to the terminal`

