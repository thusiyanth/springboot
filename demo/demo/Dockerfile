# Dockerfile
FROM openjdk:17-jdk-slim
EXPOSE 8090

# Copy the compiled JAR file into the Docker image
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Specify the command to run your application
ENTRYPOINT ["java", "-jar", "/app.jar"]
