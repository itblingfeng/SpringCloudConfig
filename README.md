# SpringCloudConfig
```html
spring:
  cloud:
    config:
      uri: http://localhost:8888
      label: master
      profile: dev
      name: microservices-eureka
```
```html
spring:
  cloud:
    config:
      label: master
      profile: dev
      uri: http://localhost:8888
      name: microservices-provider-user
```
```html
spring:
  cloud:
    config:
      name: microservices-consumer-movie-feign-with-hystrix
      uri: http://localhost:8888
      profile: dev
      label: master
```
