# Simple template to quick start a dev server with docker-compose and Traefik

> Traefik is awesome tool to setup a reverse proxy with automatic Letsencrypt TLS negotiation

## Quck start
1. Clone this repository
1. Fit .env configs for each service you need
1. Start traefik with command `cd ./traefik && docker-compose up -d`
1. Start Postgres, Adminer and Dozzle if you need it. 

## Generate Secret hash string for basic auth using apr1 algorithm (Apache variant of the BSD algorithm)
```shell
openssl passwd -apr1 # or with optional parameter -salt xxxxxxxx
```
