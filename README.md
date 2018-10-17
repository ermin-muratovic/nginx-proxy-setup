# nginx-proxy-setup
Proxy setup for docker hosting using nginx, jwilder/docker-gen and jrcs/letsencrypt-nginx-proxy-companion.

Requires docker network "docket_net". Create the network with
```
docker network create docker_net
```