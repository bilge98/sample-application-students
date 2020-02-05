FROM openjdk:11-jre
ENV MYAPP_HOME /opt/api
WORKDIR $MYAPP_HOME
COPY /target/*-exec.jar $MYAPP_HOME/api.jar

ENTRYPOINT java -jar api.jar