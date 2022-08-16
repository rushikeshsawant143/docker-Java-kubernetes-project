# FROM tomcat:latest
FROM java:8
WORKDIR /
# ADD target/productcatalogue-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/app.jar
ADD target/productcatalogue-0.0.1-SNAPSHOT.jar app.jar
# ADD product-catalogue.yml app-config.yml
EXPOSE 8020
# CMD ["catalina.sh", "run"]
CMD ["java","-jar","app.jar","server"]
# ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.jar", "server", "app-config.yml"]
