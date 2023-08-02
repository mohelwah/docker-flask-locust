# docker-flask-locust
A docker + flask + locust demo project

[Flask + Locust YouTube Walkthrough](https://www.youtube.com/watch?v=bUEYe6AqlXE)



## This is one of my recipes in the upcoming book Cloud Computing for Data

### [Cloud Computing for Data Analysis Book](https://leanpub.com/cloud4data)
This book is being written "just in time", with a weekly release schedule.
## docker commands:
- build docker image:
  docker build -t tagname .
- run docker:
  docker run -d -p 8080:8080 tagname
- list images:
  docker images
- list or running container
  docker container ls
- enter to docker container:
  docker exec -it CONTAINER ID
- exit from container:
  exit
- commmit container:
  docker commit CONTAINER ID mohelwah/container-name:latest
- docker push:
  docker push IMAGENAME:TAG
