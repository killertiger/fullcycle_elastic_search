# Description

Set up beats:
- metricbeat - Checks CPU, Memory, Disk i/o, Network etc..
- heartbeat - Checks ping and http uptime

# Running the project

## Execute the following steps for the first time
```
$ docker network create observability
```


## Running the elastic search
```
$ docker compose up -d
```
Access the following url from you browser:
http://localhost:5601/


## Running django app example for APM
```
$ cd app
$ docker compose up -d
```
Access the following url from you browser:
http://localhost:8000/exemplo/
