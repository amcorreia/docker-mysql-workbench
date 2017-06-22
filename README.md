#amcorreia/docker-mysql-workbench
==================

[![Docker Stars](https://img.shields.io/docker/stars/amcorreia/docker-mysql-workbench.svg)](https://hub.docker.com/r/amcorreia/docker-mysql-workbench/)
[![Docker Pulls](https://img.shields.io/docker/pulls/amcorreia/docker-mysql-workbench.svg)](https://hub.docker.com/r/amcorreia/docker-mysql-workbench/)
[![Docker Build](https://img.shields.io/docker/automated/amcorreia/docker-mysql-workbench.svg)](https://hub.docker.com/r/amcorreia/docker-mysql-workbench/)
[![Layers](https://images.microbadger.com/badges/image/amcorreia/docker-mysql-workbench.svg)](https://microbadger.com/images/amcorreia/docker-mysql-workbench)
[![Version](https://images.microbadger.com/badges/version/amcorreia/docker-mysql-workbench.svg)](https://microbadger.com/images/amcorreia/docker-mysql-workbench)


Docker container image with [Mysql Workbench](https://www.mysql.com/products/workbench/)

### How to run

```sh
$ docker run -d --rm -it  -v /tmp/.X11-unix:/tmp/.X11-unix --name workbench amcorreia/docker-mysql-workbench
```

### How to build

```sh
$ docker build -t amcorreia/docker-mysql-workbench .
```
