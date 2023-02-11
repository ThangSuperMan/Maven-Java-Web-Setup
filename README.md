## Basic web app with maven

```bash
# Generate the maven java project with template webapp
mvn archetype:generate -DgroupId=com.javawebtutorhehe -DartifactId=SampleWebApplicationHaha -DarchetypeArtifactId=maven-arc
hetype-webapp -DinteractiveMode=false

# Require jetty plugin added in pom.xml
# Install the jetty (just for the first time) and run the server based on the port number
mvn jetty:run
```
