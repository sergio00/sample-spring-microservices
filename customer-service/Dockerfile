FROM openjdk
# Add Maintainer Info
LABEL maintainer="slsergioxavier@gmail.com"
ADD target/customer-service.jar customer-service.jar
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
EXPOSE 3333