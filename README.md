# A simple Dash app - run on Dokcer
#### Note: here it's assumed that you already have your docker installed.

## To start the service
Clone this Dash-based app package. Change directory - in command line - to this package downloaded.

Execute command in order to build docker image for this app. 

```
$ docker-compose up --build -d
```
## To end the Service

```
docker-compose stop
```

## To kill the Service
```
kill -9 $(lsof -ti :8070)
```
