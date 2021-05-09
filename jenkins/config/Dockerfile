FROM docker.io/doubledna/openjdk_wj:latest
WORKDIR /opt/
COPY build.jar /opt/
COPY start.sh /opt/
# RUN yum install git -y
ENTRYPOINT ["/bin/sh", "/opt/start.sh"]