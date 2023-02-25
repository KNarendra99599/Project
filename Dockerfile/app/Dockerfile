FROM tomcat:8.5-jdk8-corretto
LABEL "Project"=""
LABEL "Author"="narendra"
RUN rm -rf  /usr/local/tomcat/webapps/*
COPY target/tomcat-app.war  /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh","run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps
