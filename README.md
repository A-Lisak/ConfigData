# ConfigData
---
spring:
  application:
    name: lab-3-client
  cloud:
    config:
      uri: http://localhost:8001
  profiles:
    active: northamerica
---
server:
  port: 8002
```
