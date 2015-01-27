## Ekylibre (PPA) Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ekylibre](http://www.ekylibre.org/) on [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/ubuntu/) published by [Botux](http://botux.fr).


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download `docker pull dockerfile/ekylibre`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/ekylibre" github.com/xx/xx`)


### Usage

    docker run -it --rm dockerfile/ubuntu

    docker run -d -e POSTGRES_USER=ekylibre -e POSTGRES_PASSWORD=ekylibre --name db postgres
