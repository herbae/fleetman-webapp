FROM openjdk:8u131-jre

MAINTAINER Iury Lazoski "lazoski@gmail.com"

ADD maven/fleetman-0.0.1-SNAPSHOT.jar webapp.war

EXPOSE 8080

CMD ["java","-Dspring.profiles.active=docker-demo","-Djava.security.egd=file:/dev/./urandom","-jar","webapp.war"]
