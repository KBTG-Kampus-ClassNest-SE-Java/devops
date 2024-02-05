FROM amazoncorretto:17.0.9-alpine3.18

WORKDIR /app
ADD . .
RUN ["./gradlew","bootJar"]
ENTRYPOINT ["java", "-jar", "build/libs/demo-0.0.1-SNAPSHOT.jar"]