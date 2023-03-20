### Dockerfiles
Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.
### How to build image form Dockerfile
...
docker build -t [docker-hub-url]/[your-user-name]/[image-name]:version .  # Here docker-hub-url is optional
...
## How to Push Image to Docker Hub
...
docker push [docker-hub-url]/[your-user-name]/[image-name]:version  # Here docker-hub-url is mandatory while pushing the image to repo 
...

docker run -it -d -p 80:80 nginx
docker exec -it 78975c23c651 bash---

cd /usr/share/nginx/html/---default docker directory 
cd /var/lib/docker/volumes---place where docker stored its information

docker volume create [name of the volume]

docker run -d -v nginx:

-p host-port: containerport
-v host-path: container-path
docker run -d -v nginx:/usr/share/nginx/html nginx -p 80:80 nginx
