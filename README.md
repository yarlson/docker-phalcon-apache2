docker-phalcon-apache2
======================

Docker image based on Ubuntu 14.04 (trusty) with the latest stable [Phalcon PHP Framework](http://phalconphp.com) with apache 2.4 webserver installed.

This image is using the [szeist/phalcon](https://index.docker.io/u/szeist/phalcon/) image as base image.


### Installation
```sh
$ docker pull szeist/phalcon-apache2
```

### Usage
```sh
$ docker run -v /document/root/on/your/mahine:/var/www -p 8080:80 szeist/phalcon-apache2
```

The apache webserver with Phalcon PHP framework will available on TCP port 8080 on your machine. The document root will be the folder you specified after the -v switch. 
