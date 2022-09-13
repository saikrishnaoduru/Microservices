FROM openjdk:1.8-jre-slim
WORKDIR usr/src
#EXPOSE 9196
ADD ./target/cloud-config-server-0.0.1-SNAPSHOT.jar /usr/src/cloud-config-server-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "cloud-config-server-0.0.1-SNAPSHOT.jar"]