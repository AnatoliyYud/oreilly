FROM docker/whalesay:latest

MAINTAINER Anatoliy Yudaev <trouble93@yandex.ru>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
