# Configurations
**1. Apache Tomcat kill**  
**2. Angular setup**  
**3. Thymleaf**  
**4. SSMS**  
**5. MySQL**  
**6. MongoDb**  

# Web
## 1. ![](https://img.shields.io/badge/Apache%20Tomcat-F8DC75.svg?style=for-the-badge&logo=Apache-Tomcat&logoColor=black)
```
netstat -ano | findstr 8080
taskkill /F /pid 1088
```
## 2. ![](https://img.shields.io/badge/Angular-DD0031.svg?style=for-the-badge&logo=Angular&logoColor=white)
```
ng new your_workspace --create-application false
cd your_workspace
ng generate application testApp
ng serve
```
## 3. ![](https://img.shields.io/badge/Thymeleaf-005F0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white)
```html
<html xmlns:th="http://www/thymeleaf.org"> - notacja odwołujaca do biblioteki 

```

# Entities
## 4. ![](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927.svg?style=for-the-badge&logo=Microsoft-SQL-Server&logoColor=white)
```java
spring.datasource.url=jdbc:sqlserver://serverNameOrAdress;databaseName=nazwaBazyDanych;encrypt=true;trustServerCertificate=true
spring.jpa.database-platform=org.hibernate.dialect.SQLServerDialect
spring.datasource.driver-class-name=com.microsoft.sqlserver.jdbc.SQLServerDriver
spring.datasource.username=user
spring.datasource.password=User1234!
```
## 5. ![](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)
```java
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://localhost:3306/schema?useSSL=false
spring.datasource.username=springuser
spring.datasource.password=ThePassword
#spring.jpa.show-sql: true
```

## 6. ![](https://img.shields.io/badge/MongoDB-47A248.svg?style=for-the-badge&logo=MongoDB&logoColor=white)
```java
spring.data.mongodb.uri=mongodb://localhost/shema
```
