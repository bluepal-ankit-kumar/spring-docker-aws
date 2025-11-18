FROM eclipse-temurin:17-jdk

WORKDIR /app

# Copy JAR file from target folder to the container
COPY target/spring-docker-aws-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
