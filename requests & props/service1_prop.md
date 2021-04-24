#props for [[service1]]

---

You can use this properties file when debugging needed for service1:

```properties
server.port=8080
logging.level.root=INFO
app.redis.topic=testTopic
spring.redis.sentinel.master=redis-master
spring.redis.password=abcdef
spring.redis.database=5
feign.hystrix.enabled=true
```