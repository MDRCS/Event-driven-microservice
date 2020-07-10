# Event driven Microservices in Python

This repository holds a simple event-driven microservice
showcase implementing the architecture style

[![Build Status](https://travis-ci.org/Lawouach/event-driven-microservice.svg?branch=master)](https://travis-ci.org/Lawouach/event-driven-microservice)

Please read the [documentation](http://event-driven-microservice-showcase.readthedocs.org/en/latest/) regarding this project.

## TODO

This repository is not complete yet, there are many
tasks still to carry to get the full picture:

* implement an aggregate for commands
* better configuration scheme
* propose a much nicer REST API
* automatically discover services at startup
* wait for kafka to be available before starting microservices
* ~~wrap the microservices into containers~~
* orchestrate said containers to demonstrate scale and fault-tolerance