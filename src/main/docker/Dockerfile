# Micro Service - Hystrix Dashboard
# Author GeekTech
# Version 1.0.0

FROM geekcarnegie/centos:1.0
MAINTAINER GeekTech
VOLUME /tmp
ADD hystrix-dashboard-1.0.0.jar hystrix-dashboard.jar
RUN bash -c 'touch /hystrix-dashboard.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/hystrix-dashboard.jar"]