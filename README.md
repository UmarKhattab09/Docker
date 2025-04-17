# Docker
 
### Learning Docker - 4/12/2025
- Some basics and overview of Docker. 


### 4/15/2025 12:45AM
#### Docker Images
#### Docker Container
#### Building Dockerfile
     - Learning how to create a Dockerfile and convert it into an Image and furthur use it in a container
#### Docker Networking
     - Creating a Docker Bridge Network. 
     - Merging 2 Seperate container ( SQL Database, Flask APP)

#### Docker Volume and Storage 
     - Failing of the database or any other container can lead to the loss of the a Data.
     - Creating a Volume on the host and saving the data on it. To prevent dataloss when a Container Crash or Restarts


### 4/17/2025 5:37PM
#### Docker Compose:
     - Instead of writing  `docker run` for each container. We can make a compose file which will automatically run all the containers required. (Will Upload Soon)
     - For Example, SQL DataBase and Flask App are 2 individual containers that we need to run. Instead of running them individually. We write `docker compose up` which runs all the container in that docker file

