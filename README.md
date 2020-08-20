# jenkins-docker
Simple Jenkins server running in docker

## How to run
docker-compose up

## First Time Setup
1. After a few seconds, run `docker logs jenkins-dood` to get the admin password
2. Click install suggested plugins (it should finish instantly)
3. Choose jenkins URL (TODO see what this should be on the ec2 instance)


# TODO
- create cloud-formation script to create an EC2 instance with this
   - needs to download and install docker (look at other dockerfiles for jenkins-dood)
   - needs to use this docker-compose and run it (alternative is just use docker run commands)
- re-organize repo to split up cloud formation and docker stuff
- figure out what to do about docker image tag/version
- be agile and show them what I have first

