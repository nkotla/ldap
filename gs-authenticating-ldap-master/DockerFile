FROM tomcat:8.0.43-jre8
ADD target/authenticating-ldap-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/
EXPOSE 8080
CMD chmod +x /usr/local/tomcat/bin/catalina.sh
CMD ["catalina.sh", "run"]
