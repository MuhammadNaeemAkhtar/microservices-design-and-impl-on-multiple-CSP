FROM adoptopenjdk/openjdk11:jdk-11.0.2.9-slim
WORKDIR /opt
ENV PORT 8080
EXPOSE 8080
COPY *.jar /opt/vote_app-0.0.1-SNAPSHOT.jar
ENTRYPOINT exec java $JAVA_OPTS -jar vote_app-0.0.1-SNAPSHOT.jar