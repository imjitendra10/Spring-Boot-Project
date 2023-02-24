# Spring-Boot-Project

# This project about REST API with Spring Boot, H2 Database, JPA, and Hibernate. I have performed the basic CRUD (Create, Read, Update, Delete) operations.

# Used Spring tool suite.

# Created the several packages such as ProductEntity, ProductDTO, ProductServiceAPI, ProductServiceImpl, ProductServiceRepository.

# updated maven dependencies.

# Configure database
# As I have added H2database dependency to the pom.xml, so let’s configure the database URL, username, and password. also configure hibernate properties for auto-creating the tables based on the entity in application.properties.
server.port=2023
spring.datasource.driver-class-name=org.h2.Driver
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:h2:mem:ProductService_DB
spring.datasource.username=sa
spring.datasource.password=password
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.h2.console.enabled=true
#JPA
spring.jpa.show.sql=true
spring.jpa.properties.hibernate.format_sql=true

# As I have added spring.h2.console.enabled this tells spring to start H2 database administration inside browser, It can be accessible by visiting this url http://localhost:2023/h2-console


# Run the application
