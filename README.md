# ![RealWorld Example App](quarkus-logo.png)

> ### Quarkus Framework codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.

This codebase was created to demonstrate a fully fledged fullstack application built with [Quarkus](https://quarkus.io/) including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the Quarkus community styleguides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.


# How it works

This application basicaly uses Quarkus Framework with Java with some other modules known to development community:

* Hibernate
* Jackson for JSON
* H2 in memory database
* JPA Criteria
* Auth0 java-jwt

### Organization of project:
```
domain/
    builder/
    config/
    constants/
    entity/
        persistent/
        exception/
    repository/
        impl/
    resource/
        service/
            impl/
    security/
        service/
            impl/        
web/
```


# Getting started

> npm install, npm start, etc.
