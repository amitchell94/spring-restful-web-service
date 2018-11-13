# Spring RESTful Web Service
A skeleton project to demo implementing a RESTful Web Service using the Spring framework.

This service will accept HTTP GET requests at:
```
http://localhost:8080/greeting
```

and respond with a JSON representation of a greeting:

```
{"id":1,"content":"Hello, World!"}
```

You can customize the greeting with an optional `name` parameter in the query string:

```
http://localhost:8080/greeting?name=User
```

The `name` parameter value overrides the default value of "World" and is reflected in the response:

```
{"id":1,"content":"Hello, User!"}
```

## Getting Started

You can get started by cloning the project to your local machine:
```
$ git clone https://github.com/amitchell94/spring-restful-web-service.git
```

### Prerequisites

In order to execute this program you will need to install the Java JDK.

### Installing
To get the development environment up and running, you will first need to create the database.

## Built With

* [Gradle](https://gradle.com/) - Dependency Management

## Authors

* **Andy Mitchell** - *Initial work* - [GitHub](https://github.com/amitchell94)

## Acknowledgments

* Created using the [Spring RESTful Web Service Tutorial](https://spring.io/guides/gs/rest-service/) 
