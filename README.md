# CurrencyConversionApp
A Spring boot app built with microservices architecture that provides
REST API-s to :
1. Check conversion rate of one currency against another.
2. Show the equivalent amount of currency A in currency B.

In this app, the following techs are used:

1. Spring Data JPA and H2 in memory Database.
2. Hibernate ORM tool.
3. Feign client to call one service from another.
4. Spring Cloud Load Balancer (called from feign) is used for client side laod balancing.
5. Eureka naming server as Service registry.
6. Spring Cloud Gateway as API gateway forcross cutting concerns.
7. Resilience4j as a circuit breaker.
8. Sleuth and Zipkin for distributed tracing.
9. RabbitMQ for Message Queuing.
10. Docker for containarizig services.

