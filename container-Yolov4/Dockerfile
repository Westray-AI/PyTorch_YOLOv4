FROM ultralytics/yolov3
#FROM yolov3:latest

RUN mkdir -p /usr/src/mish-cuda
RUN mkdir /Documents
WORKDIR /usr/src/mish-cuda
RUN git clone https://github.com/JunnYu/mish-cuda.git .
RUN python setup.py build install
WORKDIR /Documents