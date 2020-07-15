# Microservices with NodeJs

## Prerequisite

- [RabiitMQ](https://www.rabbitmq.com/download.html)
- [Node](https://nodejs.org/en/download/)

## Queue System

- Start Queue by running `/usr/local/sbin/rabbitmq-server`

## Service registry

- Start Service Registry
- `cd service-registry; npm i; npm start;`

## Services

### Feedback Service

- Start Feedback Service
- `cd feedback-service; npm i; npm start;`

### Speaker Service

- Start Speaker Service
- `cd speakers-service; npm i; npm start;`

## Main App

- Start the web server
- `cd conference-app; npm i; npm start;`
- Open the browser and go to `http:localhost:8090`
