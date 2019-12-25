FROM tomcat:8-jre8

RUN rm -rf /usr/share/tomcat/webapps/*

cp /var/lib/jenkins/workspace/GameOfLife/gameoflife-web/target/gameoflife.war /usr/share/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
