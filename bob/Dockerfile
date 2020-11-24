#JDK
FROM java:8

#jar
COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

#run
ENTRYPOINT ["java", "-jar", "/bob.jar"]

#port
EXPOSE 8081