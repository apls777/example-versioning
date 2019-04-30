FROM tensorflow/tensorflow:1.13.1-gpu-py3-jupyter

# install requirements
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

# install wget and unzip
RUN apt-get update && apt-get -y install wget unzip
