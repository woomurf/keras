FROM tensorflow/tensorflow:latest-gpu

RUN mkdir /workspace

WORKDIR /workspace
COPY . /workspace

RUN pip install keras numpy pillow

CMD python3 mnist_mlp_v4.py
