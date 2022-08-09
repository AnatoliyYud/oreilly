FROM docker/whalesay:latest
*beacause is not working with debian:wheezy

RUN apt-get update && apt-get install -y cowsay fortune
ENTRYPOINT ["/usr/games/cowsay"]
