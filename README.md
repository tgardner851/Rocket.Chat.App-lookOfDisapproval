# Rocket.Chat.App-lookOfDisapproval

Shows a look of disapproval targetted at a user.

# Deprecated

This project will no longer be maintained by me, I have retired my Rocket.Chat server in favor of a Matrix Synapse server.

## Configuration

TODO

## Docker
A Dockerfile and docker-compose are provided.

Build the docker image and run it to deploy to your server:
`docker build -t rocketchatapp_lookofdisapproval . && docker run -it --rm -e URL=YOUR_SERVER -e USERNAME=YOUR_USERNAME -e PASSWORD=YOUR_PASSWORD rocketchatapp_lookofdisapproval`

Build the docker image and run docker-compose to deploy to your server:
`docker build -t rocketchatapp_lookofdisapproval . && docker-compose run --rm -e URL=YOUR_SERVER -e USERNAME=YOUR_USERNAME -e PASSWORD=YOUR_PASSWORD rocketchatapp_lookofdisapproval`
