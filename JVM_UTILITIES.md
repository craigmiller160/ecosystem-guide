# JVM Utilities

This is a section covering all the utility libraries I've written to support JVM-based applications.

## Authentication

All authentication/authorization for all applications is delegated to the `sso-oauth2-server`. To help this, all code to integrate with this OAuth2 server has been wrapped in easly usable libraries.

[@craigmiller160/oauth2-utils-core](https://github.com/craigmiller160/oauth2-utils-core) = The core business logic for integrating with the OAuth2 server, without any framework-specific dependencies.

[@craigmiller160/jaxrs-oauth2-utils](https://github.com/craigmiller160/jaxrs-oauth2-utils) = A wrapper for `oauth2-utils-core` to work with JAX-RS implementations, specifically Jersey.

[@craigmiller160/spring-oauth2-utils](https://github.com/craigmiller160/spring-oauth2-utils) = A wrapper for `oauth2-utils-core` to work with Spring Boot applications.

## General Libraries

Just some random libraries I've written.

[@craigmiller160/spring-web-utils](https://github.com/craigmiller160/spring-web-utils) = Utility code I wrote to support Spring Boot web applications.

[@craigmiller160/legacy-date-converter](https://github.com/craigmiller160/legacy-date-converter) = An older library containing re-usable functions for converting between the different Java date APIs.


