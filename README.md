# Spring API

## Steps to quickstart

```bash
./gradlew bootRun
```

## Build

```bash
./gradlew build

# Run after build
java -jar build/libs/gs-rest-service-0.1.0.jar
```

### Test endpoints

```bash
curl -XGET localhost:8080/greeting
curl -XGET localhost:8080/greeting?name=Harshit
```