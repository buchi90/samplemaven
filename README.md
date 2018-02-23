Drools Spring integration using Maven
=====================================

This a project is mavenized version of the 2 Drools examples [Banking example](http://docs.jboss.org/drools/release/5.2.0.Final/drools-expert-docs/html/ch09.html#d0e9044) and [Pricing and Decision Table Rules example] (http://docs.jboss.org/drools/release/5.2.0.Final/drools-expert-docs/html/ch09.html#d0e9371).

In order to start this example run 

```ruby
mvn clean test
```

You will see all the test successful. It is completely integrated with Spring framework and works with spring-core version 3.0.2-release. There are some issues hence it is not working with 3.1.1.release, I am still exploring. Feel free to modify. Refer this [blog](http://krishnasblog.com/2012/09/20/spring-drools-spring-business-rules-sample/) for more details.
