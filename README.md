1. Lists all running Docker containers.

         docker ps
2. To show all containers (running + stopped)
   
        docker ps -a
3. Lists all Docker images stored locally on your machine.

        docker images
4. Connect to an existing conatiner

        docker exec -it <container_name_or_id> bash
5. Check Docker version

        docker --version
6. Remove an image

       docker rmi <image_id>
7. Stop a running container

        docker stop <container_id>
9. Start a stopped container

        docker start <container_id>   


 
