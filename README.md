# CurrencyConversionApp
A Spring boot app built with microservices architecture that provides
REST API-s to :
1. Check conversion rate of one currency against another.
2. Show the equivalent amount of currency A in currency B.

In this app, the following techs are used:

1. Spring Data JPA and H2 in memory Database.
2. Hibernate ORM tool.
3. Feign client to call one service from another.
4. Eureka naming server as Service registry.
5. Eureka + Spring Cloud Load Balancer (called from feign) is used for client side laod balancing.
6. Spring Cloud Gateway as API gateway for cross cutting concerns.
7. Resilience4j as circuit breaker.
8. Sleuth and Zipkin for distributed tracing.
9. RabbitMQ for Message Queuing.
10. Docker for containarizig services.

Some Interactions:

API call:

![](https://github.com/AbidSaleh/CurrencyConversionApp/blob/main/assets/cc_USD_BDT.png)

Api call with feign:

![](https://github.com/AbidSaleh/CurrencyConversionApp/blob/main/assets/cc_feign.png)

Eureka Dashboard:

![](https://github.com/AbidSaleh/CurrencyConversionApp/blob/main/assets/eureka.png)

Zipkin traces:

![](https://github.com/AbidSaleh/CurrencyConversionApp/blob/main/assets/zipkin_trace1.png)

![](https://github.com/AbidSaleh/CurrencyConversionApp/blob/main/assets/zipkin_trace2.png)
