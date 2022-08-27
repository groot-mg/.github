## Hi there 👋

:receipt: These repositories represent a microservices architecture based in a shopping/e-commerve api.

Some techniques and tools used:
* API Gateway
* Service discovery
* Microservices 
* Databases: PostgreSQL and Cassandra
* Security layer - Keycloak with OpenID Connect
* Observability - Prometheus, Alert Manager and Grafana dashboards

## General Architecture Diagram
<p align="center">
    <a href="https://www.hackerrank.com/mauriciogeneroso">
        <img height=450 src="./images/shopping-api-general-diagram.png" alt="General diagram">
    </a>
</p>

## How to run
These repositories are not hosted anywhere, you might be able to run them in your local machine, it just depends if your machine is powerful enough. 

Requirements:
* Java 17
* Docker and docker-compose

To run everything together, a docker local setup is already provided on [docker-local-setup](https://github.com/groot-mg/docker-local-setup). It will build the necessary `.jar` files, create the local docker images, and start up the containers.

## Documentation
Each repository has its own documentation on Readme or Wiki pages, but a deeper explanation how everyhing work together is provided on the repo [docs](https://github.com/groot-mg/docs)
