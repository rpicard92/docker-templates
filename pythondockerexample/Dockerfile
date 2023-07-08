FROM ubuntu:latest

RUN apt update
RUN apt install python3 -y

WORKDIR /usr/app/src

COPY test.py ./

CMD [ "python3", "./test.py"]