# eureka-server
Netflix Eureka service discovery server for Widgets Are Us microservices project

## Frameworks and Dependencies
- Spring Boot 2.4.3
- Spring Cloud 2020.0.1
- Docker
- Logstash
- RabbitMQ

## Details

- Uses RabbitMQ to receive configuration updates from the config server.
- Registers itself with the Netflix-Eureka service discovery service
- Logging is handled by an ElasticSearch Logstash Kibana (ELK) stack
- Zipkin is used for tracing metrics
