# springboot-activemq-sample

SpringBoot application using embedded ActiveMQ. A more complete example can be found here:

    https://memorynotfound.com/spring-boot-embedded-activemq-configuration-example/
    
In this project we are runnign embedded ActiveMQ.

If you want to use an external ActiveMQ change the `application.properties` file like this:

    spring.activemq.broker-url=tcp://127.0.0.1:61616
    spring.activemq.user=admin
    spring.activemq.password=secret
    
