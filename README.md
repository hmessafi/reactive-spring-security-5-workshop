[![License](https://img.shields.io/badge/License-Apache%20License%202.0-brightgreen.svg)][1]
[![Build Status](https://travis-ci.org/andifalk/reactive-spring-security-5-workshop.svg?branch=master)](https://travis-ci.org/andifalk/reactive-spring-security-5-workshop)
[![Release](https://img.shields.io/github/release/andifalk/reactive-spring-security-5-workshop.svg?style=flat)](https://github.com/andifalk/reactive-spring-security-5-workshop/releases)

# Reactive Spring Security 5 Workshop

This is a hands-on workshop on securing a reactive Spring Boot 2.0 based web application using Spring Security 5.0.

## Topics

Topics that will be covered by this workshop are:

* [Reactive Streams Programming](http://www.reactive-streams.org/) with [Project Reactor](https://projectreactor.io) and [Spring WebFlux](https://docs.spring.io/spring/docs/current/spring-framework-reference/web-reactive.html)
* [OWASP Top 10 Application Security Risks 2017](https://www.owasp.org/index.php/Top_10-2017_Top_10)
* Base concepts of [Spring Security 5](https://spring.io/projects/spring-security) (i.e. Security Web Filter Chain)
* Authentication
* Authorization
* Secure Password encryption and encryption upgrading
* [Security Headers](https://securityheaders.com)
* Coverage of common security challenges like
  * Session fixation
  * CSRF
  * SQL injection
  * XSS
* Automated security testing
* [OAuth 2.0](https://tools.ietf.org/html/rfc6749) and [OpenID Connect 1.0](https://openid.net/specs/openid-connect-core-1_0.html)

## Requirements

To start the workshop you need:

* [Java JDK version 8, 9 or 11](https://openjdk.java.net/install/)
* A Java IDE ([Eclipse](https://www.eclipse.org/), [STS](https://spring.io/tools), [IntelliJ](https://www.jetbrains.com/idea/), [VS Code](https://code.visualstudio.com/), [NetBeans](https://netbeans.org/), ...)
* To test the RESTful services on the command line [curl](https://curl.haxx.se/download.html) would be helpful to install
* The workshop tutorial documentation ([html](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html) or [pdf](https://github.com/andifalk/reactive-spring-security-5-workshop/raw/master/docs/workshop-tutorial.pdf))
* [The initial reactive application to be made secure](https://github.com/andifalk/reactive-spring-security-5-workshop/tree/master/00-library-server)
* The [REST API documentation](https://andifalk.github.io/reactive-spring-security-5-workshop/api-doc.html) of the initial reactive application

## Workshop structure

The workshop is split up into the following parts:

* [Step 1: Auto Configuration](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html#_step_1_auto_configuration)
* [Step 2: Customize Authentication](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html#_step_2_customize_authentication)
* [Step 3: Add Authorization](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html#_step_3_add_authorization)
* [Step 4: Security Testing](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html#_step_4_security_testing)
* [Step 5: OAuth2/OpenID Connect](https://andifalk.github.io/reactive-spring-security-5-workshop/workshop-tutorial.html#_step_5_oauth2_openid_connect)


## License

Apache 2.0 licensed

Copyright (c) by 2019 Andreas Falk

[1]:http://www.apache.org/licenses/LICENSE-2.0.txt