FROM eclipse-temurin:11-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
USER 12051
COPY dist/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
