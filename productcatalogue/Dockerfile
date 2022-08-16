# FROM tomcat:latest
FROM openjdk:8-jre
# ADD target/productcatalogue-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/app.jar
ADD target/productcatalogue-0.0.1-SNAPSHOT.jar app.jar
# ADD product-catalogue.yml app-config.yml
EXPOSE 8020
# CMD ["catalina.sh", "run"]
ENTRYPOINT ["java","app.jar"]
# ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.jar", "server", "app-config.yml"]
