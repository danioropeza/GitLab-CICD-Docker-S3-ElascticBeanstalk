FROM openjdk:8-jdk-alpine
RUN addgroup -S spring && adduser -S spring -G spring
USER spring:spring
ARG JAR_FILE=build/libs/*.jar
ENV AMAZONPROPERTIES_ACCESSKEY="secret"
ENV AMAZONPROPERTIES_BUCKETNAME="secret"
ENV AMAZONPROPERTIES_ENDPOINTURL="secret"
ENV AMAZONPROPERTIES_REGION="secret"
ENV AMAZONPROPERTIES_SECRETKEY="secret"
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]