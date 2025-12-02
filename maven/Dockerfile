FROM maven:3.9.11-eclipse-temurin-8-alpine

RUN apk update && apk add git

WORKDIR /root/homework7
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git && cd ./boxfuse-sample-java-war-hello && mvn -B package
