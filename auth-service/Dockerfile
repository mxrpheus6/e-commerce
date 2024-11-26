FROM openjdk:21

WORKDIR /app

COPY auth-service/build/libs/auth-service-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]