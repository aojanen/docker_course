FROM openjdk:8

EXPOSE 8080

WORKDIR /usr/src/app

COPY ./spring-example-project/* ./

COPY ./spring-example-project/.mvn/ ./.mvn

RUN chmod +x ./mvnw

RUN ./mvnw package

RUN java -jar ./target/docker-example-1.1.3.jar

