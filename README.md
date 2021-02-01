
Unofficial API for eToro, built on top of https://github.com/ok24601/etoro-api

## RUN

### docker run

1. docker run --shm-size=1g -p 8088:8088 -e LOGIN=user -e PASSWORD=ooooooooo -it --rm --name my-etoro-api etoroapi

or 

### docker compose

1. edit .env with user and password for etoro
2. docker-compose up