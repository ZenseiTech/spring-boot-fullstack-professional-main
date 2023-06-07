[![CICD](https://github.com/amigoscode/spring-boot-fullstack-professional/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/amigoscode/spring-boot-fullstack-professional/actions/workflows/deploy.yml)

https://amigoscode.com/p/full-stack-spring-boot-react

#To run the H2 database:
- Download from http://h2database.com/html/download.html
- Run as follows: 
  - java -cp h2*.jar org.h2.tools.Server -ifNotExists
  - jdbc:h2:tcp://localhost:9092/~/Projects/Java/spring-boot-fullstack-professional-main/database/db

_ run maven install then from target dir:
  - java -jar demo-0.0.1-SNAPSHOT.jar --server.port=8081 
