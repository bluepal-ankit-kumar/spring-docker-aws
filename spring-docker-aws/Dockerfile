FROM openjdk:11
COPY target/spring-docker-aws  /usr/aap/

WORKDIR /usr/app/
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "spring-docker-aws.jar"]

