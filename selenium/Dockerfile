FROM wangjianyong/jupyter
MAINTAINER Jianyong Wang <wangjianyongscu@gmail.com>
ENV REFRESHED_AT 2016-12-14

#############
RUN apt-get update && apt-get install -y \
  git \
  phantomjs \
  python-lxml \
  mongodb \
  python-bs4
RUN pip install -y \
    senelium \
