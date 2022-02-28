# HelloServlet

## Packaging and running the webapp

The web application can be packaged with the command "mvn package" and run with the command "mvn jetty:run"

## Servlet containers

A Java servlet runs inside a servlet container. Maven Jetty is a servlet container and so is Apache Tomcat. 

A servlet container reads from the src/main/webapp/WEB-INF/web.xml file to get data about servlets and servlet mappings, and stores this data inside an instance of the ServletContext class.

In order to make a Java web application using servlets, you need to run the servet inside a servlet container, like Jetty or Tomcat.
