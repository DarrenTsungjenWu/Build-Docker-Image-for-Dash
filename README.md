# A simple Dash app

## To start the service
Clone this Dash-based app package. Change directory - in command line - to this package downloaded.

Execute command in order to build docker image for this app. 
# Note: here it's assumed that you already have your docker installed.

```
$ docker-compose up --build -d
```
## To end the Service

```
docker-compose stop


# Kill Service
```
kill -9 $(lsof -ti :8070)
```
