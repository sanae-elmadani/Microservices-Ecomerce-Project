FROM openjdk:8
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} mcommande.jar
ENTRYPOINT ["java","-jar","/mcommande.jar"]
EXPOSE 9101