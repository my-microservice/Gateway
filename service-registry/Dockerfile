FROM openjdk:11-jdk
WORKDIR /
ADD build/libs/service-registry-*.jar app.jar
ENV JAVA_OPTS = ""
EXPOSE 8761
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar app.jar"]