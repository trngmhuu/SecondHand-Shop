# EmployeeService/Dockerfile
FROM openjdk:17
EXPOSE 8081
COPY target/EmployeeService-0.0.1-SNAPSHOT.jar EmployeeService-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/EmployeeService-0.0.1-SNAPSHOT.jar"]