# Enterprise shopping platform- Spring Boot (JSP + Hibernate)

Production-oriented Java e-commerce web application built with Spring Boot, JSP, Spring Security, and Hibernate SessionFactory.

This project follows a layered MVC architecture and supports role-based access for admin and customer workflows.

<br/><br/>

<h1>🛒 Enterprise shopping platform Spring Boot</h1>
 
<p>A production-oriented Java e-commerce web application built with Spring Boot, JSP, Spring Security, and Hibernate — featuring role-based access for admin and customer workflows.</p>


## Highlights

- Server-rendered e-commerce app (JSP views)
- Spring Security authentication and role-based authorization
- Custom Hibernate SessionFactory configuration (non-Spring-Data JPA runtime)
- MySQL-backed persistence with DAO and service layers
- Admin modules for products, categories, and customer listing
- User modules for registration, login, profile management, and product browsing
- Jenkins pipeline file included for CI/CD bootstrap

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-11-ED8B00?style=flat-square&logo=openjdk&logoColor=white&labelColor=1a1a2e" alt="Java 11"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-2.6.4-6DB33F?style=flat-square&logo=springboot&logoColor=white&labelColor=1a1a2e" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Spring%20Security-5.x-6DB33F?style=flat-square&logo=springsecurity&logoColor=white&labelColor=1a1a2e" alt="Spring Security"/>
  <img src="https://img.shields.io/badge/Hibernate-ORM-59666C?style=flat-square&logo=hibernate&logoColor=white&labelColor=1a1a2e" alt="Hibernate"/>
  <img src="https://img.shields.io/badge/MySQL-8.x-4479A1?style=flat-square&logo=mysql&logoColor=white&labelColor=1a1a2e" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=flat-square&logo=apachemaven&logoColor=white&labelColor=1a1a2e" alt="Maven"/>
</p>

- Java 11
- Spring Boot 2.6.4
- Spring MVC
- Spring Security
- Hibernate ORM (via `LocalSessionFactoryBean`)
- JSP + JSTL + Tomcat Jasper
- MySQL 8 connector
- Maven

## Project Structure

```text
src/main/java/com/jtspringproject/JtSpringProject/
  configuration/     # Security config
  controller/        # MVC controllers
  dao/               # Data access layer
  models/            # Entities
  services/          # Business layer
  repository/        # Spring Data repository (partial)
  HibernateConfiguration.java
  JtSpringProjectApplication.java
src/main/resources/
  application.properties
src/main/webapp/views/
  *.jsp
basedata.sql
pom.xml
```
