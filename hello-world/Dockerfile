FROM tomcat:latest
RUN cp -R  /usr/local/tomcat/webapps.dist/*  /usr/local/tomcat/webapps
COPY /var/lib/jenkins/workspace/project-demo/hello-world/webapp/target  /usr/local/tomcat/webapps/

