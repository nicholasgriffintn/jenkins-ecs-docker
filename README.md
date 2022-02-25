# Jenkins ECS Docker

This is a repo for running a local Docker instance of Jenkins with Docker Compose. This is mainly for personal testing, but could be deployed to a server. I have added some ECS config as well to deploy it automatically.

## Install and setup

Run the following command to install the required dependencies and setup the project:

`./install.sh`

## Start container

Run this command to start the container:

`docker-compose up -d`

## Stop container

Run this command to stop the container:

`docker-compose down`

## Accessing Jenkins locally

Once you have started the container, you should be able to access the Jenkins instance locally at: `http://localhost:8081/` (it might take a while to start up initially!).