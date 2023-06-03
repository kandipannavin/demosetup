FROM openjdk:17

COPY target/sb-docker-app.jar  /usr/app/

WORKDIR /usr/app/

ENTRYPOINT ["java", "-jar", "sb-docker-app.jar"]
