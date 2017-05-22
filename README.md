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

result-types?
interceptors?
default-interceptor-ref?
default-action- ref?
default-class-ref?
global-results?
global-exception-mappings?
action*
