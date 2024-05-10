# FROM openjdk:8u151-jdk-alpine3.7

# EXPOSE 8070

# ENV APP_HOME /usr/src/app

# COPY target/shopping-cart-0.0.1-SNAPSHOT.jar $APP_HOME/app.jar

# WORKDIR $APP_HOME

# ENTRYPOINT exec java -jar app.jar

FROM openjdk:17-jdk-alpine
MAINTAINER baeldung.com
COPY target/docker-message-server-1.0.0.jar message-server-1.0.0.jar
ENTRYPOINT ["java","-jar","/message-server-1.0.0.jar"]
