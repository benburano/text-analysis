Rcommendations for managing persistend data in docker:
You have to use Docker volumes to persistent data.
Volumes are easier to back up or migrate applications.
We can share among volumes among multiple containers.
Valumes are best practises for managing data within the docker container, 
because volume does not increase the size of the containers using it.
