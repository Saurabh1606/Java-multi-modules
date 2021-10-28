FROM frolvlad/alpine-oraclejdk8:slim

ADD order-service.jar /usr/local/order-service/

WORKDIR /usr/local/order-service/

CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "order-service.jar"]
