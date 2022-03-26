FROM openjdk:17-oracle
ARG JAR_FILE=world/target/*.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8100
ENTRYPOINT ["java","-jar","/app.jar"]