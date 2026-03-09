docker ps  
Shows all currently running containers.


docker ps -a  
Shows all containers (running and stopped).


docker images  
Lists all Docker images available on the system.


docker pull nginx  
Downloads the nginx image from Docker Hub to your local system.


docker run nginx  
Creates and starts a container from the nginx image.


docker run -it nginx /bin/bash  
Starts a container and opens an interactive bash terminal inside it.


exit  
Exits from the running container terminal.


docker start container_name  
Starts a stopped container again.


docker attach container_name  
Attaches your terminal to a running container.


Ctrl + P + Q  
Detaches from the container without stopping it.


docker run -itd --name my-nginx nginx /bin/bash  
Creates and runs a container in detached (background) mode with a custom name.


docker stop my-nginx  
Stops a running container.


docker rm my-nginx  
Removes a container from the system.