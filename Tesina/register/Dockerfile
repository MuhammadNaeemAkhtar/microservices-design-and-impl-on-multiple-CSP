FROM adoptopenjdk/openjdk11:jdk-11.0.2.9-slim
WORKDIR /opt
ENV PORT 8081
EXPOSE 8081
COPY *.jar /opt/voters-0.0.1-SNAPSHOT.jar
ENTRYPOINT exec java $JAVA_OPTS -jar voters-0.0.1-SNAPSHOT.jar