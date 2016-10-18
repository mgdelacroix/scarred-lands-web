FROM ubuntu:xenial
MAINTAINER Miguel de la Cruz <miguel@mcrx.me>

RUN apt-get update && apt-get install -y wget

RUN wget https://github.com/spf13/hugo/releases/download/v0.17/hugo_0.17-64bit.deb -O /tmp/hugo.deb && \
    dpkg -i /tmp/hugo.deb && apt-get install -fy && rm /tmp/hugo.deb

WORKDIR /site
