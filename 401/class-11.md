# Spring App Basics

To build application with **Spring MVS** we need:

* IDE

* jdk 1.8 or later

* Gradle 4+


## Starting with Spring Initializr

To generate a new project with the required dependencies (Spring Web, Thymeleaf, and Spring Boot DevTools) for **Gradle** user visit the [Spring Initializr](https://start.spring.io/).

The code bellow is for `build.gradle` file:

```
plugins {
	id 'org.springframework.boot' version '2.4.3'
	id 'io.spring.dependency-management' version '1.0.11.RELEASE'
	id 'java'
}

group = 'com.example'
version = '0.0.1-SNAPSHOT'
sourceCompatibility = '1.8'

repositories {
	mavenCentral()
}

dependencies {
	implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
	implementation 'org.springframework.boot:spring-boot-starter-web'
	developmentOnly 'org.springframework.boot:spring-boot-devtools'
	testImplementation 'org.springframework.boot:spring-boot-starter-test'
}

test {
	useJUnitPlatform()
}
```

We can also initialize the project manually by visit [https://start.spring.io.](https://start.spring.io/), or if the IDE has the Spring Initializr integration, you can complete this process from your IDE.

## Create a Web Controller

* `@Controller` : it is an annotation used for marks a class as Controller and for handling the HTTP requests.

* `GetMapping` : it is an annotation used to map the class with the specified URL name. It ensures the specific HTTP GET requests are maped to specific method.

* `@RequestParam` : it is an annotation  used to read the form data and bind it automatically to the parameter present in the provided method.

## Run the Application

* `@SpringBootApplication` : it is convenience annotation that use to auto-configuration, component scan and be able to define extra configuration on application class.

* `@EnableAutoConfiguration` : Tells Spring Boot to start adding beans based on classpath settings, other beans, and various property settings.

* `@Configuration` : allow to register extra beans in the context or import additional configuration classes

## Build an executable JAR

We can run the application from command line with Gradle. We can also build a single executable JAR file that contains all the necessary dependencies, classes, and resources and run that. The advantages of building an executable jar aare makes it easy to ship, version, and deploy the service as an application throughout the development lifecycle, across different environments.

# Spring MVC and Thymeleaf

**Thymeleaf** is a Java library . It is template engine for processing and creating HTML, XML, JavaScript, CSS, and text.

1. **Spring model attributes**

Spring MVC calls the pieces of data that can be accessed during the execution of views model attributes. The equivalent term in Thymeleaf language is context variables.

2. **Request parameters**

Easily accessed in Thymeleaf views. Request parameters are passed from the client to server.

3. **Session attributes**

Session attributes can be accessed by using the `session.` prefix or Or by using `#session`.

4. **ServletContext attributes**

To access ServletContext attributes in Thymeleaf you can use the `#servletContext.` prefix.

5. **Spring beans**

Thymeleaf allows accessing beans registered at the Spring Application Context with the `@beanName` syntax.