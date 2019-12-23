FROM tomcat:8-jre8

RUN rm -rf /usr/local/tomcat/webapps/*

COPY gameoflife.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8085
CMD ["catalina.sh", "run"]
