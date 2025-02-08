FROM amazoncorretto:17-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8080

# docker build --build-arg JAR_FILE=<PATH/TO/JAR-FILE> .
# docker run -p 8080:8080 <CONTAINER-ID>