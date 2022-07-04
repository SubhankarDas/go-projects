# Go Projects

## 1. Learning

Implementing simple functionalities using the Go language features.

## 2. MicroGo - Simple Go based Microservice

A sample microservice architecture implementation providing a RESTful API for CRUD operations on a students data.

### Docker

`docker-compose up`

### Cassandra

Open shell for <b>cassandra</b> container

`docker-compose exec cassandra /bin/bash`

<b>Login to Cassandra</b>

`cqlsh -u cassandra -p cassandra`

<b>Run CQL queries</b>

* students-service - To create the keyspace and tables run the commands in the folder 

    <i>microservices > students-service > cql > schema.cql</i>