# CentOS Jira Docker Container

[![Docker Automated build](https://img.shields.io/docker/automated/v0rts/docker-centos-jira.svg?maxAge=2592000)](https://hub.docker.com/r/v0rts/docker-centos-jira/)
[![Docker Automated build](https://img.shields.io/docker/pulls/v0rts/docker-centos-jira.svg?maxAge=2792000)](https://hub.docker.com/r/v0rts/docker-centos-jira/)
[![Docker Automated build](https://img.shields.io/docker/stars/v0rts/docker-centos-jira.svg?maxAge=2792000)](https://hub.docker.com/r/v0rts/docker-centos-jira/)

Docker CentOS Jira Container

## How to Build

This container is built with any commit to the `master` branch of this repo. If you wish to build the image locally, do the following:

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. `cd` into this directory.
  3. Run `docker build -t centos-jira .`

## How to Use

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. Pull this image from Docker Hub: `docker pull v0rts/docker-centos-jira:latest` (or use the tag you built earlier, e.g. `centos-jira`).
  3. Run a container from the image: `docker run -d -p 8080:8080 v0rts/docker-centos-jira`
  4. Connect to the Jira instance `https://localhost:8080`
  5. Attach to container via shell: `docker exec -t -i container_id /bin/bash`

## Notes



## Author

Created by v0rts (v0rts@getitsolutions.net)

