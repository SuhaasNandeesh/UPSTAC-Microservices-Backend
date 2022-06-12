FROM openjdk:14-jdk-alpine
LABEL key="upgrad"
ADD ./target/upstac-api-0.0.1-SNAPSHOT.jar /opt/app/upstac-api-document-0.0.1-SNAPSHOT.jar
WORKDIR /opt/app
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8082
ENTRYPOINT [ "java", "-jar", "/opt/app/upstac-api-document-0.0.1-SNAPSHOT.jar"]