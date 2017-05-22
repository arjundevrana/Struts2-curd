#Simple CRUD demo

[![Build Status](https://travis-ci.org/strutsathon/struts2-crud-example.png)](https://travis-ci.org/strutsathon/struts2-crud-example)

How to start:

    mvn jetty:run
    
    
    
up vote
7
down vote
accepted
Got it! The order matters.

Order in struts.xml matters:

1.result-types?
2.interceptors?
3.default-interceptor-ref?
4.default-action- ref?
5.default-class-ref?
6.global-results?
7.global-exception-mappings?
8.action*
