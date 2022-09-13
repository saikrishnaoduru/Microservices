FROM openjdk:1.8-jre-slim
WORKDIR usr/src
#EXPOSE 9192
ADD ./target/order-service-0.0.1-SNAPSHOT.jar /usr/src/order-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "order-service-0.0.1-SNAPSHOT.jar"]