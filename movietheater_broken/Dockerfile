# Use image: Linux and Java

FROM alpine/java:22-jdk

# Copy application to container

COPY target/app.jar /app.jar

# Copy application.properties to container (Remove from jar)

COPY src/main/resources/application.properties /application.properties

# Start application

ENTRYPOINT ["java","-jar","/app.jar"]