FROM itzg/minecraft-server:latest
LABEL maintainer "sf"

RUN apk add --no-cache \
  tzdata

RUN cp /usr/share/zoneinfo/Europe/Paris /etc/localtime \
  && echo "Europe/Paris" > /etc/timezone
