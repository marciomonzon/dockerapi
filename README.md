# .NET API with Docker

Docker Commands:

Check Docker Version: docker --version

Build docker to a target: docker build -t your_id/dockerapi:version_number .

Check docker images: docker images

Docker run: docker run -p 8080:80 your_id/dockeraoi (image name)
(8080 is the container port and is mapping to 80. That is the port exposed on dockerfile)

check images status: docker ps
show a list of running containers

stop a container: docker stop image_id

start a container: docker start imagem_id

Push to Docker Hub: docker push your_id/dockerapi

