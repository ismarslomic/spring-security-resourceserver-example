# OAuth2 Resource Server Example

> Simple hello world example using OAuth2 Resource Server in Spring Security v5.1.1.RELEASE (and Spring Boot v2.1.0.RC) to validate JWT token and authenticate the REST API request

## Getting up and running

```(bash)
$ mvn clean install
$ mvn spring-boot:run
```

## Request API

`GET http://localhost:8081/` with Google OAuth Access Token provided as `Bearer Token` in `Authorization` header. You can configure other 
provider as well, by modifying `jwk-set-uri` property in `application.yml`