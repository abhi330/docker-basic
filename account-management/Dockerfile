FROM openjdk:17-jdk-slim
COPY target/account-management-0.0.1-SNAPSHOT.jar account-management.jar
EXPOSE 9001
ENTRYPOINT ["java", "-jar", "account-management.jar"]
