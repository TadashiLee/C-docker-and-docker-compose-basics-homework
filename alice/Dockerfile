#JDK
FROM java:8

#jar
COPY build/libs/alice-0.0.1-SNAPSHOT.jar alice.jar

#run
ENTRYPOINT ["java", "-jar", "/alice.jar"]

#port
EXPOSE 8080