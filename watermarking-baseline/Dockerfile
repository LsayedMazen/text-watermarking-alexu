FROM ubuntu

RUN apt-get update \
    && apt-get install -y python3 python3-pip \
    && pip3 install --break-system-packages tira click pandas torch transformers accelerate tqdm

ADD baseline.py /