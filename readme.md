# Docker-LAMP
This is simplest docker compose configuration for old LAMP projects based on Apache 2, PHP 5.6 (FPM), Maria DB 10.1.

## Installation
- Clone this repo using `git clone`.
- Put some files into html directory.
- Run `docker-compose up -d` .
- Open in browser: http://localhost:30101

## Networking

Due migration to https://github.com/jwilder/nginx-proxy and Docker 1.9, need to setup user network for container communicating.

To create network with name "*www*" run `docker network create --driver bridge www`


## Configuration
Additional configurations can be added into relative subdirs