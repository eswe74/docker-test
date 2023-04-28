## test image in local environment

    docker build . -t eswe/node-web-app

    docker run -p 49170:8080 -d eswe/node-web-app

    curl http://localhost:49170

## create new repository to github and add app to git 

## github action: login to docker hub 
    
    https://www.youtube.com/watch?v=CDWLWjnYSGg

## github action: push image to docker hub 

    https://www.youtube.com/watch?v=HwATG0ygxzU

## docker pull eswe/node-web-app:latest

## docker run --detach --publish 5000:80 eswe/node-web-app:latest

## test http://localhost