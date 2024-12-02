FROM ubuntu:focal

RUN apt-get update && \
    apt-get install -y \
    python3-pip 

RUN pip3 install --upgrade pip

ADD requirements.txt /requirements.txt
RUN pip3 install -r /requirements.txt

COPY src /src

CMD ["python3", "/src/hello-world.py"]
