# Docker Commands

- `docker build . : build the image`

- `docker ps : lists all the running containers`

- `docker run -p 3000:80 e9775276737e : run the container with the image name on the end(we need to expose the port 3000 in order to run it in the browser).`

- `docker stop container_name : used to stop the running container(container_name: use docker ps to get the list of running containers)`

- ` docker ps -a: lists all the containers built on your system`
