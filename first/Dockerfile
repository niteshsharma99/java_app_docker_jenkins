FROM openjdk:8-jre-alpine

RUN mkdir /App

COPY  target/test-0.0.1-SNAPSHOT.jar /App/hello.jar

EXPOSE 3333

CMD java -jar /App/hello.jar
