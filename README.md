# docker-nginx-static-html-demo

## Prerequisites 

- docker installed 

## System Configuration at time of test 

- MacOS - 
- Docker - 

## Build Image

Run the following command on the terminal:
`docker build -t nginx-static-html-image:v1 .`

To list the created images run the command on the terminal:
`docker images`

**TODO:** Add image here

## Run the Docker Container

Run the following command to run the HTML container server:
`docker run -d -p 45678:80 nginx-static-html-image:v1`

To list all the containers running run this command on the terminal:
`docker ps -a`

**TODO:** Add image here

## Test

Run the following command to ensure the server is running:
`curl localhost:45678`

You can also view it in the browser now by going to `localhost:45678` and you should see your HTML:
![docker-nginx-static-html-demo-image](images/docker-nginx-static-html-demo-image.png?raw=true "Browser Shreenshot")


# Cleanup

To stop the container that is running use this command 
`docker stop {container_id}`

To delete the container that was created use this command
`docker rm {container_id}`

To delete the docker image that was created 
`docker rmi {image_id}`
