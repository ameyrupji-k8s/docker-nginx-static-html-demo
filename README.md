# docker-nginx-static-html-demo

## Prerequisites 

- docker installed 

## Build Image

Run the following command:
`docker build -t nginx-static-html-image:v1 .`

To list the created images run the command:
`docker images`

## Run the Docker Container

Run the following command to run the HTML container server:
`docker run -d -p 45678:80 nginx-static-html-image:v1`


## Test

Run the following command to ensure the server is running:
`curl localhost:45678`

You can also view it in the browser now by going to `localhost:45678` and you should see your HTML:
![docker-nginx-static-html-demo-image](images/docker-nginx-static-html-demo-image.png?raw=true "Browser Shreenshot")
