FROM frolvlad/alpine-oraclejdk8:slim

ADD website.jar /usr/local/website/

WORKDIR /usr/local/website/

CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "website.jar"]