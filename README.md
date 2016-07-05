# php-interact
This is the Docker base image for PHP-FPM containers.

### How to build

```sh
$ docker build -f Dockerfile-5.5 -t phpfpm:5.5 .
$ docker build -f Dockerfile-5.6 -t phpfpm:5.6 .
$ docker build -f Dockerfile-7.0 -t phpfpm:7.0 .
