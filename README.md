# jee-hello-world

A simple hello world example with a servlet in order to try intellij idea community edition + remote debug

## Intellij idea community edition setup
 - create a simple webapp module using the maven archetype
 - add a javaee-api with the scope "provided", in the pom for compilation (don't forget to configure a repository in the maven settings.xml)
 - create a servlet and add the corresponding mapping in web.xml
  
## Serving the webapp with tomcat 
- Use the tomcat7-maven-plugin (add the dependency in the pom.xml)
- use the command tomcat7:run

## Remote debugging
- just run the maven plugin in debug mode