FROM openjdk:17.0.2


RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

RUN mkdir -p /opt/projects/mall4j

WORKDIR /opt/projects/mall4j

ADD ./yami-shop-admin/target/yami-shop-admin-0.0.1-SNAPSHOT.jar ./

EXPOSE 8085

CMD java -jar -Xmx256m -Dspring.profiles.active=docker yami-shop-admin-0.0.1-SNAPSHOT.jar
