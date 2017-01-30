FROM lwieske/java-8:server-jre-8u112-slim
VOLUME /tmp
ADD ${fullName}.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]