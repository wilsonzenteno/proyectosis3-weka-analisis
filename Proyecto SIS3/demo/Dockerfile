FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY demo/target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]