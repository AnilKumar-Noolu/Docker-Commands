# Docker-Commands
Following are the list of most commonly used Docker Commands:

-> docker pull: This Command is used to download a Docker image from a registry, such as DockerHub.

-> docker images: This Command will give you a list of all the Docker images that were there on your server.

-> docker ps: This Command is used to list all running Docker Containers on the host machine.

-> docker ps -a : It will list all Containers whether they are running or not.

-> docker run -d -p <ports> <image_name> : This command will run the docker container in background and it will respective mentioned ports.

-> docker logs <Container_name> : This command is used to show the conatiner logs
  
 -> docker start <container_id> : This command is used to start a Docker container.

-> docker stop <container_id> : This command is used to stop a running Docker container.

-> docker rmi <Image_name> : This command is used to remove a Docker image from host machine, you can remove multiple images at a same time.

-> docker rm <container_id> : This command is used to remove a stopped Docker container from a host machine.

-> docker rm -f <container_id> : This command is used to remove a Docker container forcefully without stopping from a host machine.

-> docker exec : This command is used to execute a command inside a running Docker Container.
  
-> docker tag: This command is used to tag the image with a new name or add a tag to the end of it.
  
-> docker login: This command is used to login to a registry, such as Docker Hub with username and password.
  
-> docker push <image_name> : This command is used to upload a Docker image to a registry, such as Docker Hub.

-> docker volume create <volume_name> : This command is used to create a volume.

-> docker rm $(docker ps -a -q -f status=excited): This command will delete all the container that have a status of excited.
-q returns numeric ID's, -f returns filters based on condition given
