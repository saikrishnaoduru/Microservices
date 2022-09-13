FROM openjdk:1.8
WORKDIR usr/src
#EXPOSE 8989
ADD ./target/cloud-gateway-0.0.1-SNAPSHOT.jar /usr/src/cloud-gateway-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "cloud-gateway-0.0.1-SNAPSHOT.jar"]