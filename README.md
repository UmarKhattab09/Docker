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

#### Docker MultiStage: 
      - It is use to decrease the File Size, by simply adding stages. 
      - In terms of an example: Suppose we have a container of 1GB, most of the Space occupied by the PYTHON Image, and the reason we are using it to install the requirements.txt ( Because most Python images do not have all the requirements). We can create a multistage where we can use the first Python Image to download the requirements.txt and replace it with a PYTHON-SLIM file which is basically Python in a            small factor.

### INTRODUCTION TO KUBERNETES : 
      - Now, after all the capabilities Docker has, we still don't use Docker in Production or Deployment Level because a container may crash because of High Volume of Traffic. or It can crash be crashed and              removed easily. To avoid all that , we Use Kubernetes. 
      - You can suppose Kubernetes or K8'S as a system that manages Docker Containers. It can restart them if the docker crashes, controls the high volume of traffic by increasing the scalability. All of this can         be handle by K8's. 
      
