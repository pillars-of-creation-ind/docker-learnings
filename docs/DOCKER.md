# DOCKER

```bash
docker build . # build docker image
docker image ls # list of all docker images
docker image rm IMAGE_ID # delete docker image
docker build -t image_name . # build docker image with name
docker run -d image_name # run docker with predefined name
docker run -d --name container_name image_name # run docker in detched mode with specific name
docker ps # check all the containers
docker rm container_name -f # force fully removed docker
docker run -p 4000:3000 -d --name container_name image_name
# run docker in detched mode with specific name
# with port `-p 4000:3000` 4000: run docker file and 3000: for node application
docker exec -it container_name bash
docker ps # shows you running containers
docker ps -a # shows all containers
docker logs container_name # show logs related with docker container, here for "node-app"
docker volume ls # show all volums
docker run
  -v $(pwd):/app
  -p PORT_OF_DOCKER_ENVIRONMENT:PORT_OF_APPLICATION
  -d
  --name container_name image_name
docker rm container_name -fv # delete container with volumes
```
