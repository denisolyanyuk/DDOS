FROM kalilinux/kali-rolling:latest
ENV DEBIAN_FRONTEND noninteractive
ENV DEBCONF_NONINTERACTIVE_SEEN true

RUN apt update && apt -y install kali-linux-large && sudo apt update
RUN apt install inetutils-ping
