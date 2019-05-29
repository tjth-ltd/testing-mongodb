# testing-mongodb

A simple Mongodb server for testing purposes - This is not recommended to run in a production environment as there is no authentication setup by default.

# Installation

* Clone this repository to your docker host 
* Run the below command to start the docker container

```
cd testing-mongodb
docker-compose up -d 
```

# Accessing

The Docker container forwards port 27017 to the host networking so will be accessible externally on port 27017

```
mongo --host [docker-host-ip]
```