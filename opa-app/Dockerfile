FROM adoptopenjdk/openjdk11
VOLUME /tmp
COPY target/opa-app-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]


# docker build . -t opa-app