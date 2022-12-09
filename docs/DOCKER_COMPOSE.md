# Docker Compose

```bash
version: "3" # docker version to support your features
services:    # each container refers as service (list them)
  node-app:   # name of container (app)
    build: .  # build dockerfile and it's path
    ports:    # multiple ports on which docker runs (docker_container_port:app_port)
      - "4000:3000"
    volumes:  # list down volumes associated with app
      - ./:app
      - ./app/node_modules
    environment:  # set environment variable (u can list down as many)
      - PORT=3000
    env_file:   # set environment variables from file
      - ./.env  # path to .env file
  postgres:
  redis:
```

```bash
docker-compose up -d # to up container
docker-compose down # tear down image and container
docker-compose down -v # tear down image, container and volumes
```
