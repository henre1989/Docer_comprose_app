FROM tomcat:9
RUN apt update
RUN mv webapps webapps2 && mv webapps.dist/ webapps && mkdir war
RUN cp /usr/local/tomcat/war/hello-1.0.war /usr/local/tomcat/webapps/