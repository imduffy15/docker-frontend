# docker-frontend Docker hub image

[![](https://images.microbadger.com/badges/image/imduffy15/docker-frontend.svg)](https://microbadger.com/images/imduffy15/docker-frontend "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/imduffy15/docker-frontend.svg)](https://microbadger.com/images/imduffy15/docker-frontend "Get your own version badge on microbadger.com")
[![Build Status](https://travis-ci.org/imduffy15/docker-frontend.svg?branch=master)](https://travis-ci.org/imduffy15/docker-frontend)
[![Docker Stars](https://img.shields.io/docker/stars/imduffy15/docker-frontend.svg?style=flat)](https://hub.docker.com/r/imduffy15/docker-frontend/)
[![Docker Automated build](https://img.shields.io/docker/automated/imduffy15/docker-frontend.svg?style=flat)]()
[![Docker Pulls](https://img.shields.io/docker/pulls/imduffy15/docker-frontend.svg)]()

## Overview

This lightweight alpine docker image provides front end tooling:

 - python 2.7
 - node 10.4.1
 - libpng

## Build

For doing a manual local build of the image:  
`make docker_build`

This image is fully automated via travisci.org.  
For reference this .travis.yml file can be validated via:  
`docker run --rm -it -v $(pwd):/project caktux/travis-cli lint ./travis.yml`
