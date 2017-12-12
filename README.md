# Jenkins-Pipelines-Lab

### Run Jenkins with Docker

Create a new directory and a new file called jenkins-compose with the content.
```
version: '2'
services:
  jenkins:
    image: "jenkins/jenkins:lts-alpine"
    ports:
      - "8080:8080"
```

Run the service with docker-compose

Go to the url http://localhost:8080/ and configure jenkins by following the instructions and 

Install the suggested plugins and create an admin-user

### Install maven in jenkins

In jenkins, go to http://localhost:8080/configureTools/

Add maven and name it 'M3' and save.

### Create a new Job

Go to new item and select pipeline.

In 'Pipeline box, select '


