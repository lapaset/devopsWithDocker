FROM ubuntu:18.04

COPY search.sh .

RUN apt-get update && apt-get upgrade && apt-get install -y curl

CMD ./search.sh