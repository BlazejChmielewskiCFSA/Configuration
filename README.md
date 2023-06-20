# Configurations
**1. SSMS**  
**2. MySQL**  

## Entities
## 1. ![](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927.svg?style=for-the-badge&logo=Microsoft-SQL-Server&logoColor=white)
```java
datasource.setServerName(value) 
datasource.setDatabaseName(value)
```
## 2. ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)
```java
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://${MYSQL_HOST:localhost}:3306/db_example
spring.datasource.username=springuser
spring.datasource.password=ThePassword
#spring.jpa.show-sql: true
```
