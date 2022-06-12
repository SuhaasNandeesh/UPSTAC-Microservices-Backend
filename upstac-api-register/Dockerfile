FROM openjdk:14-jdk-alpine
LABEL key="upgrad"
ADD ./target/upstac-api-0.0.1-SNAPSHOT.jar /opt/app/upstac-api-register-0.0.1-SNAPSHOT.jar
WORKDIR /opt/app
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8090
ENTRYPOINT [ "java", "-jar", "/opt/app/upstac-api-register-0.0.1-SNAPSHOT.jar"]