# docker-with-jnlp-and-docker

Dockerfile with:

docker
docker-compose
aws-cli
ecs-cli

YOU MUST RUN COMMAND FOR DOCKER TO SHARE WITH HOST.

docker run -v /var/run/docker.sock:/var/run/docker.sock  -td docker-with-jenkins-slave-and-docker YOUR COMMAND
