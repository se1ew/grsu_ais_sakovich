FROM ubuntu:20.04

RUN apt-get update && \
    apt-get install -y openjdk-8-jdk && \
    apt-get clean


COPY PingPongSakovich.java /
RUN javac PingPongSakovich.java
EXPOSE 8080
CMD ["java", "PingPongSakovich"]
