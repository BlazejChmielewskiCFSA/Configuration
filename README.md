# Configurations
**1. Apache Tomcat kill**
**2. SSMS**  
**3. MySQL**  

##
## 1. ![](https://img.shields.io/badge/Apache%20Tomcat-F8DC75.svg?style=for-the-badge&logo=Apache-Tomcat&logoColor=black)
```java
netstat -ano | findstr 8080
taskkill /F /pid 1088
```
## Entities
## 2. ![](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927.svg?style=for-the-badge&logo=Microsoft-SQL-Server&logoColor=white)
```java
datasource.setServerName(value) 
datasource.setDatabaseName(value)
```
## 3. ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)
```java
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://localhost:3306/schema?useSSL=false
spring.datasource.username=springuser
spring.datasource.password=ThePassword
#spring.jpa.show-sql: true
```
