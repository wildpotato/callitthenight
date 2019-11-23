FROM pytorch/pytorch

RUN apt-get update && apt-get install -y \
vim

#ADD requirements.txt && \
#pip install -r requirements.txt
RUN apt-get update && apt-get install -y python3-pip
RUN pip install torchvision 
RUN pip install matplotlib 
RUN pip install gluoncv
RUN pip install mxnet-mkl

