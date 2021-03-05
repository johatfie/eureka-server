# Netflix Eureka service discovery server

Provides service discovery for Widgets Are Us microservices project

## Technologies
- Java 11
- Spring Boot 2.4.3
- Spring Cloud 2020.0.1
- Docker
- Logstash

## Details

- Uses RabbitMQ to receive configuration updates from the config server.
- Logging is handled by an ElasticSearch, Logstash, and Kibana (ELK) stack
- Zipkin is used for visualizing user transactions across multiple services
