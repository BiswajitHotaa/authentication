# Spring Boot Authentication Starter

Quick-start project for username/password authentication using Spring Boot 3, Spring Security, Thymeleaf, JPA, and H2 DB.

## Features
- Register, login, logout
- BCrypt password hashing
- H2 in-memory database & H2 console
- Minimal Thymeleaf pages with clean CSS

## Run
```bash
./mvnw spring-boot:run
# or
mvn spring-boot:run
```
Then open http://localhost:8080

## Notes
- Access H2 console at `/h2-console` (JDBC URL: `jdbc:h2:mem:testdb`).
- Default role is `ROLE_USER`. Extend entity/service for more roles/claims.
