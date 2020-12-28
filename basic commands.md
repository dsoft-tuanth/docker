Pull an image from the Docker Hub\
sudo docker pull image_name

create container\
sudo docker run -v <forder_in_computer>:<forder_in_container> -p <port_in_computer>:<port_in_container> -it <image_name> /bin/bash

Show Kernel information\
uname -a

Lists available images\
docker images

delete a image\
docker rmi {image_id/name}

List the running containers\
docker ps

list the stop containers\
docker ps -a

delete a container\
docker rm -f {container_id/name}

stat a container\
docker start {new_container_name}

Access the running container\
docker exec -it {new_container_name} /bin/bash

