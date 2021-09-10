# study
## General introduction
study is a docker-environment for the scientific writing.
This container is based on the [rocker/tidyverse](https://hub.docker.com/r/rocker/tidyverse "dockerhub") including rstudio, TinyTeX and rticles.
## Usage
First, pull the docker image from docker-hub using docker-compose.
```
cd .docker_study && docker-compose up
```
Second, attach to the rstudio at [localhost:8787](https://localhost:8787).
Note that, initial password is `0000` and username is `rstudio`.