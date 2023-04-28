## test image in local environment

    docker build . -t eswe/node-web-app

    docker run -p 49170:8080 -d eswe/node-web-app

    curl http://localhost:49170

## create new repository to github and add app to git 

## github action: login to docker hub 
    
    https://www.youtube.com/watch?v=CDWLWjnYSGg

## github action: push image to docker hub 

    https://www.youtube.com/watch?v=HwATG0ygxzU

## pull image from dockerhub

    docker pull eswe/node-web-app:latest

## run container
    
    docker run --detach --publish 5000:8080 eswe/node-web-app:latest

## test 

    curl http://localhost:5000