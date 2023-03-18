## Hi there 👋

:receipt: These repositories represent a microservices architecture and a microservice for product registration/listing for a shopping/e-commerve api.

Some techniques, frameworks and tools used:
* API Gateway ([Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway))
* Service discovery ([Spring Netflix Eureka](https://spring.io/projects/spring-cloud-netflix))
* Microservices 
* Versioning ([axion-plugin](https://github.com/allegro/axion-release-plugin))
* Database: Cassandra
* Security layer - ([Keycloak](https://www.keycloak.org/) with OpenID Connect - integrated with [Spring Security Oauth2](https://spring.io/projects/spring-security-oauth))
* Observability: [Prometheus](https://prometheus.io/), [Alert Manager](https://prometheus.io/docs/alerting/latest/alertmanager/#alertmanager), [Slack](https://slack.com/intl/en-gb), [Micrometer](https://micrometer.io/), [Grafana Tempo](https://grafana.com/oss/tempo/), [Grafana Loki](https://grafana.com/oss/loki/) and [Grafana](https://grafana.com/) dashboards
* [Github Actions](https://github.com/features/actions) to build and test any new code
* [SonarCloud](https://sonarcloud.io/organizations/shopping-api/projects) integration for Code quality

## General Architecture Diagram
<p align="center">
    <a href="https://github.com/groot-mg/.github/blob/main/images/general-diagram.png">
        <img height=450 src="./images/general-diagram.png" alt="General diagram">
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
