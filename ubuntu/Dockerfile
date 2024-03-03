FROM debian:latest
LABEL maintainer="ermypy"
RUN apt update && \ 
    apt install -y traceroute && \ 
    apt install -y curl && \ 
    apt clean
ENTRYPOINT [ "/bin/bash" ]
