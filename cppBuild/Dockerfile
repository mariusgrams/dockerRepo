FROM ubuntu

RUN apt-get update -y && \
    apt-get autoremove -y && \
    apt-get install build-essential -y && \
    apt-get install cmake -y && \
    apt-get install pip -y && \
    pip install conan --upgrade
