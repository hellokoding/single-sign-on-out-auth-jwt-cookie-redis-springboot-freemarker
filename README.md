# Scalable Authentication, Single Sign On/Out (SSO) Example with JSON Web Token (JWT), Cookie, Redis, Java, Spring Boot, FreeMarker

## Guide
https://hellokoding.com/scalable-authentication-single-sign-on-out-sso-example-with-json-web-token-jwt-cookie-redis-java-spring-boot-freemarker/

## What you'll need
- JDK 1.7+
- Redis
- Maven 3+

## Stack
- Java
- Single Sign On/Out
- JSON Web Token
- Redis
- Cookie
- Spring Boot
- FreeMarker

## Run
- Run [Authentication Service](https://github.com/hellokoding/single-sign-on-out-auth-jwt-cookie-redis-springboot-freemarker/tree/ab60b86cd2a951899483ff5c312d297ab90fc3de): `mvn spring-boot:run`
- Run [Resource Service](https://github.com/hellokoding/single-sign-on-out-resources-jwt-cookie-redis-springboot-freemarker) 1: `mvn spring-boot:run -Dserver.port=8180`
- Run [Resource Service](https://github.com/hellokoding/single-sign-on-out-resources-jwt-cookie-redis-springboot-freemarker) 2: `mvn spring-boot:run -Dserver.port=8280`
