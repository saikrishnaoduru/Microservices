FROM openjdk:1.8-jre-slim
WORKDIR usr/src
#EXPOSE 8761
ADD ./target/service-registry-0.0.1-SNAPSHOT.jar /usr/src/service-registry-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "service-registry-0.0.1-SNAPSHOT.jar"]