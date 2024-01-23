# Docker commands

To verify docker compose version
```bash
docker-compose --version
```

To verify docker version
```bash
docker --version
```

To check docker images
```bash
docker images
```

To check docker containers
```bash
docker ps
```

To remove docker images
```bash
docker image rm <image_id>, <image_id>
```

To remove docker images
```bash
docker image rm $(docker image ls -q)
```


To remove docker containers
```bash
docker container rm -f $(docker container ls -a -q)
```

## Note: Before removing docker images we need to remove docker containers

# Docker compose commands


1. docker-compose build --help

To build docker compose
```bash
docker-compose build
```

To build docker compose with no cache
```bash
docker-compose build --no-cache
```

To start application
```bash
docker-compose up
```

To create new and build docker compose
```bash
docker-compose up --build
```

To detach mode
```
docker-compose up -d
```

To see container
```
docker-compose ps
```

To down docker compose
```
docker-compose down
```

To network
```
docker network ls
```

## NOTE: Network contains containers as per the services

