# FHEM Docker Base

## Contains

- FHEM + haus-automatisierung.com FHEM frontend style
- Apache 2 as a reverse proxy to FHEM
- Homebridge + FHEM Homebridge
- mySQL-Logging
- alexa-FHEM

## Requirements

- Docker

## Install

```
git clone https://github.com/klein0r/fhem-docker.git fhem-docker
cd fhem-docker
docker-compose up
```

## Defaults

- FHEM-WEB: 8083 (8084 and 8085 have been deleted)
- mySQL-Root-Password: adgbciBOZjwYXeATg
- mySQL-User: fhemuser
- mySQL-Password: 2jRHnEi3WuNSQAcX7

## Updating FHEM

Since all data in the container is static, you have to delete the container and recreate it to update fhem.
