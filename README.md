## Spring REST Service

A simple REST service built with Java, Spring, JPA and H2 Database using MVC architecture and Maven build tool

### GET

```java
# Connect to localhost (::1) port 8080 (#0)
# Fetch all employees
$ curl -X GET localhost:8080/employees
```

### POST

```java
# Connect to localhost (::1) port 8080 (#0)
# Add new employee
$ curl -X POST localhost:8080/employees -H 'Content-type:application/json' -d '{"name": "John Doe", "role": "Developer"}'
```

### PUT

```java
# Connect to localhost (::1) port 8080 (#0)
# Update employee
$ curl -X PUT localhost:8080/employees/1 -H 'Content-type:application/json' -d '{"name": "Samwise Gamgee", "role": "ring bearer"}'
```

### DELETE

```java
# Connect to localhost (::1) port 8080 (#0)
# Delete employee
$ curl -X DELETE localhost:8080/employees/3
```
