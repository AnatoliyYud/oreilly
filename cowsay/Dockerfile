FROM docker/whalesay:latest

RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrtypoint.sh"]
