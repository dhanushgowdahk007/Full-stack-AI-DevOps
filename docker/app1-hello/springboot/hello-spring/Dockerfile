FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY target/*.jar aap.jar
EXPOSE 8080
CMD ["java", "-jar", "app.jar"]