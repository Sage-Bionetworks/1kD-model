FROM python:3.7-bullseye

WORKDIR work
ENV VERSION=1.2.10

RUN wget https://github.com/linkml/linkml/archive/refs/tags/v${VERSION}.tar.gz -O linkml-${VERSION}.tar.gz
RUN python3 -m pip install ./linkml-${VERSION}.tar.gz

