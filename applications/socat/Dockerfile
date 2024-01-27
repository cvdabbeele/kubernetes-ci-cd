FROM alpine:3.19.1
#USER root
#Installing socat
RUN apk update && apk upgrade && apk add bash socat
COPY entrypoint.sh entrypoint.sh
ENTRYPOINT ["sh", "./entrypoint.sh"]