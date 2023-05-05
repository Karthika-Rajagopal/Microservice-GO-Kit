# Microservice-GO-Kit

Building a simple microservice with go kit, go kit is a bundle of different libraries that can be used for building microservices these libraries provide components for logging metrics, tracing , rate limiting,circuit breaking , system observability and resiliency pattern. 

There are 3 major components in go kit based application Transport layer, endpoint layer and service layer.
Transports are essentially just the ways that your microservices can communicate with one another

In this, building a simple http server which allows us to expose our microservice functions these microservice functions they get exposed known by endpoints, each of the endpoints represents a single RPC method. we gonna use the methods to convert to endpoints then that allows to expose it to the transport layer and service layer is just a business logic of the microservice itself.
