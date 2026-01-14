FROM eclipse-temurin:17-jre-alpine

WORKDIR /app

COPY app/target/devops-app-1.0.0.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
