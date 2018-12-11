# docker-php-nginx
[![Build Status](https://travis-ci.com/mchoiruln/docker-php-nginx.svg?branch=master)](https://travis-ci.com/mchoiruln/docker-php-nginx)

[![Repo](https://img.shields.io/badge/fork-github-blue.svg?logo=github&style=flat&logoColor=white)](https://github.com/mchoiruln/docker-php-nginx) 
[![Repo](https://img.shields.io/badge/repo-github-blue.svg?logo=github&style=flat&logoColor=white)](https://github.com/my-codelab/docker-php-nginx) 
[![Repo](https://img.shields.io/badge/repo-gitlab-blue.svg?logo=gitlab&style=flat)](https://gitlab.com/mchoiruln/docker-php-nginx) 
[![Repo](https://img.shields.io/badge/repo-bitbucket-blue.svg?logo=bitbucket&style=flat&logoColor=white)](https://bitbucket.org/mchoiruln/docker-php-nginx)

Sample of docker-compose with nginx and php-fpm (alpine), which say 'Hello World'

## Prerequisite
```
docker
docker-compose
docker-machine
```

## Variable
`docker-machine ip` your docker machine ip

## Usage
at base directory execute command
`docker-compose up` to run and build image

after that browse your favorite browser
go to url `http://{docker-machine-ip}`
and output is `Hello World (php)` 

`docker-compose down` to shutdown docker container