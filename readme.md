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
docker build -t image-bienvenue:1.0.0 .
```
