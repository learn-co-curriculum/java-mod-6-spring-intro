# What is Spring and SpringBoot?

## Learning Goals

- Explain what Spring is and what advantages it provides us.
- Explain how SpringBoot fits into the ecosystem.

## Spring Introduction

Spring is one of the most popular Java application frameworks in the world. An
application framework provides a set of functionalities which we can use to
build an app. They can provide several features and developers can decide which
specific features to use on their projects.

An application framework can make working with non-business logic code a lot
simpler by providing abstractions for features like security, logging, caching,
transaction, etc. Here are some of the modules that Spring provides:

- Component Container: manages object life cycle in the application.
- Data Modules: abstractions for working with different databases.
- Web Framework: abstractions, configurations, and conventions for creating
  different types of web applications.
- Security Module: enables authentication and authorization in the application.

You can check out the full list of modules provided by Spring on
[their website](https://spring.io/projects).

## Spring Core

The Spring Core provides the foundational mechanisms for integrating Spring into
applications. The core container is based on the _Inversion of Control_
principle. Instead of defining exactly how an application is controlled
(instance creation, calling methods, etc.), we define configurations which
instruct Spring on how to manage the code.

![Spring process overview](https://curriculum-content.s3.amazonaws.com/java-spring-1/spring-intro-image.png)

POJO stands for “Plain Old Java Objects” which are simply regular Java objects
without any connection to a framework. The metadata for objects is defined using
annotations. The annotations instruct Spring on how to manage the POJOs which
results in the final behavior of the application.

## SpringBoot

A Spring application requires lots of configuration. SpringBoot is a project
under Spring which takes care of most of the configurations so that developers
can focus on the business logic of their application. Here are some of the
benefits of SpringBoot:

- Easy project creation: initialization services like
  [Spring Initializr](https://start.spring.io/) provide skeleton applications
  with base configurations.
- Dependency Starters: there are bundled dependencies for specific types of
  applications.
- Dependency based auto configuration: default configurations are defined based
  on the dependencies added to the project.
- Application health/metrics monitoring.
- Embedded application server.

## Conclusion

We have learned about Spring, some of its modules, and SpringBoot in this
lesson. Spring is an application framework that makes application management
easier and SpringBoot is a sub project of Spring which streamlines most
configurations. In the coming lessons, we will learn more about both Spring and
SpringBoot.

## References

- [Spring Framework Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/index.html)
  (reference document)
- [Spring Guides](https://spring.io/guides)
