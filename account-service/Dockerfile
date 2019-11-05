FROM openjdk
# Add Maintainer Info
LABEL maintainer="slsergioxavier@gmail.com"
ADD target/account-service.jar account-service.jar
ENTRYPOINT ["java", "-jar", "/account-service.jar"]
EXPOSE 2222