#ARGS
ARG MOSQUITTO_TAG=${MOSQUITTO_TAG}

FROM ubuntu:latest

RUN apt update && \
  apt install -y mosquitto mosquitto-auth-plugin

CMD ["/usr/sbin/mosquitto", "-c", "/etc/mosquitto/mosquitto.conf"]
