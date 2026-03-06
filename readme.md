## Run Container 
```sh
docker run -v ./02-default-website/index.html:/usr/share/nginx/html/index.html -p 80:80 --name nginx_server -d nginx:1.29.5-alpine
```

## Check running containers
````sh
docker ps -a
```

## Build a Dockerfile
````sh
# Docker Image Build Command

Builds a Docker image named `image-bienvenue` with version tag `1.0.0` from the Dockerfile in the current directory.

## Usage
docker build -t image-bienvenue:1.0.0 . 

```

## supprimer une image
````sh
docker rmi image-bienvenue:1.0.0
```

# Docker Compose Startup

Starts all services defined in the docker-compose.yml file in detached mode (running in the background).

**Usage:**
docker compose up -d 
docker composer down #arrete les images

## Connect Gitlab to Github
[Youtube Gitlab-Github](https://www.youtube.com/watch?v=E4Y6A1HplWc)


