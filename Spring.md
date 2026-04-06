# Spring 
Spring is an open-source application framework for Java (and Kotlin/Groovy) that has become the de facto standard for building enterprise Java applications. 
It was created by Rod Johnson and first released in 2003 as a lighter-weight alternative to the complexity of Java EE (formerly J2EE).

At its core, Spring provides two key concepts: 

- Inversion of Control (IoC): where the framework manages object creation and wiring through a container, and 

- Dependency Injection (DI): where components declare their dependencies and Spring provides them automatically. This makes code more modular, testable, and loosely coupled.

The Spring ecosystem has grown substantially and includes several major projects. <br>
**Spring Boot** is probably the most widely used — it simplifies setup with auto-configuration, embedded servers, and opinionated defaults so you can get a production-ready app running with minimal boilerplate. <br>
**Spring MVC** and **Spring WebFlux** handle web applications (the latter for reactive/non-blocking programming). <br>
**Spring Data** simplifies database access across relational and NoSQL stores. <br>
**Spring Security** handles authentication and authorization. Spring Cloud provides tools for building distributed systems and microservices.<br>
A typical modern Spring Boot app can be started with just a few annotations like `@SpringBootApplication`, `@RestController`, and `@Autowired`, and Spring handles the rest — spinning up an embedded Tomcat or Netty server, configuring data sources, and wiring everything together.
