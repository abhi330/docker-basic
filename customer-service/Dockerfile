FROM openjdk:17-jdk-slim
COPY target/customer-service-0.0.1-SNAPSHOT.jar customer-service.jar
EXPOSE 9001
ENTRYPOINT ["java", "-jar", "customer-service.jar"]
