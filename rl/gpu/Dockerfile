FROM wangjianyong/mxnet-cuda:7.5
MAINTAINER Jianyong Wang <wangjianyongscu@gmail.com>
ENV REFRESHED_AT 2016-05-28
RUN apt-get update && apt-get install -y cmake libsdl1.2-dev python-opencv libav-tools

RUn git clone https://github.com/mgbellemare/Arcade-Learning-Environment.git && \
cd Arcade-Learning-Environment && \
cmake -DUSE_SDL=ON -DUSE_RLGLUE=OFF -DBUILD_EXAMPLES=ON . && \
make -j 4 && \
pip install . && \
cd

RUN pip install gym gym[atari]



