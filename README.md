# Dockerized / Nodejs + Express 

## Dockerfile 

Jump Start with Express  using Docker

```bash
# Build 
$ docker build -t vitorbritto/dockerized-nodejs-express .

# Run
$ docker run -p 3000:3000 -d vitorbritto/dockerized-nodejs-express

# Check Docker Processes
$ docker ps

# Remove
$ docker rm [CONTAINER_ID]

# Stop
$ docker stop [CONTAINER_ID]
```

## Docker Compose

```bash
$ docker-compose up
```


## TODO

- Add Redis
- Connect PostgreSQL