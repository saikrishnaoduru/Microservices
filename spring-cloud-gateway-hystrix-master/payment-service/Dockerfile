FROM openjdk:1.8-jre-slim
WORKDIR usr/src
#EXPOSE 9191
ADD ./target/payment-service-0.0.1-SNAPSHOT.jar /usr/src/payment-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "payment-service-0.0.1-SNAPSHOT.jar"]