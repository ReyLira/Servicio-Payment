# payment


-aplication yml

  spring:
  datasource:
    driver-class-name: org.postgresql.Driver
    url: jdbc:postgresql://localhost:5432/postgres
    username: postgres
    password: root
  jpa:
    database: postgresql
    show-sql: true
    hibernate:
      ddl-auto: create
server:
  port: 8002

  
  


