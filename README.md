# Docker-kubernetes
This is personal repo for my kubernetes and docker learning

Step to Deploy your container on aws instance.

1. dockerize your app 
  a. Create a docker file . sample file shown here
  b. Do Docker build .
  c. you can tag docker tag <> <dockerusername>/<tagname>
  
2. Create a yaml pod definetion file  like
   a. pod-hello.yml
   b. kubectl create -f <pod-hello.yml>
   c. create a service file 
   d. kubectl create -f <service-hello.yml>

