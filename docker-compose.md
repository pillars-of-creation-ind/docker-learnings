## Check Docker Compose Version

```bash
docker-compose --version
```

## Check Docker Images

```bash
docker images
```

REPOSITORY TAG IMAGE ID CREATED SIZE
instructure/dynamo-local-admin latest 4278567cc64c 6 weeks ago 548MB

```bash
docker ps
docker ps -a

```

CONTAINER ID: f91f93906b33
IMAGE: instructure/dynamo-local-admin:latest  
COMMAND: "/usr/bin/supervisor…"
CREATED: 5 weeks ago
STATUS: Up 2 weeks
PORTS: 8001-8002/tcp, 0.0.0.0:8002->8000/tc
NAMES: compassionate_jemison

```bash
docker image rm $(docker container ls -aq)
```
