# HelloServlet

## Packaging and running the webapp

This web application can be packaged with the command "mvn package" and run with the command "mvn jetty:run"

## The Maven Jetty plugin

A Java servlet runs inside a servlet container. Maven Jetty is a servlet container and so is Apache Tomcat. 

A servlet container reads from the src/main/webapp/WEB-INF/web.xml file to get data about servlets and servlet mappings, and stores this data inside an instance of the ServletContext class.
