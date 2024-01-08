# Multi-Container-Assignment
- Create a folder named  multi-container-app
- Create a folder named node. 
- Add the files Myserver.js, package.json in the node folder.
- User the readily available docker image for mysql
- Create a Dockerfile for Nodejs  application
- Write a docker file to  dockerize this node.js application.
- Download the slim version of node
- Set the work directory to the app folder. 
- Copy package.json file in the node folder to inside container
- Install the dependencies in the container
- Copy the rest of the code in the container
-  Run the node server with Myserver.js file
- EXPOSE 3000
- Next, create a docker-compose.yml under this folder
- Setup services in the docker-compose.yml file.
- Under the services section , List all the types of applications to be configured
- Fire up the containers.


# Verification:
	
Now if you hit localhost:3000/super-app you will see a response {“super”:”app”}
Also understand the docker network between the docker containers

# Delivarables

![Screenshot (2)](https://github.com/manjusha-123/Multi-Container-Assignment/assets/155906033/ba383aff-4cdb-4a50-9de7-b7b83d4273a6)

![Screenshot (3)](https://github.com/manjusha-123/Multi-Container-Assignment/assets/155906033/2ee388ca-229f-4168-93b4-ff5f25f66cb4)

