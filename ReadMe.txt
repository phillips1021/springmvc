The springmvc project is an example of how to use
Spring Web MVC framework to configure a web application 
without using any XML configuration including web.xml.

The project also shows how to create a unit test for the
Spring MVC Web controller.

Use Maven to build the war file:
   mvn -e clean package

Then copy the springmvc.war to your Servlet container.

In a web browser go to:
   http://localhost:8080/springmvc 
(your port may be different)
