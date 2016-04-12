= Portfolio service


== Build

```
mvn clean install docker:build
```

== Run

```
docker run -p 8083:8080 --rm --name dashboard --link audit:AUDIT vertx-microservice-workshop/trader-dashboard
```