from openjdk:17
EXPOSE 8080
ADD target/api-gateway-1.0.0-SNAPSHOT.jar api-gateway.jar
ENTRYPOINT ["java","-jar","/api-gateway.jar"]