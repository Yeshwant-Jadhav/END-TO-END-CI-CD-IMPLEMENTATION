# END-TO-END-CI-CD-IMPLEMENTATION

## firstally clone the code from github and attached it to jenkins(Here used to-do-list application)
## Build the code
## Crated image from docker-file and pushed that image to docker-hub
## created container using the image 
## deployed the image using container on web 

#  Manual Deploying 
## 1. clone the code from Github
##   - here is the GitFolder that we are cloned

![Screenshot (363)](https://github.com/Yeshwant-Jadhav/END-TO-END-CI-CD-IMPLEMENTATION/assets/153003135/2bdc6fe6-7aa0-4933-bbba-c5d1249b9db9)

## Craeted Docker Image using Docker-File 
##  - docker build -t to_do_app . (. means docker file present in this directory only)

## After this we created container using builded image 

## And deployed the application on http server with port 8000 (here mapped the port of container with host machine)
