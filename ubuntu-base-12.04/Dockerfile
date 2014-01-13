FROM ubuntu:12.04
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update -y
RUN apt-get install -y sudo git openssh-client bash apt-utils dialog
RUN echo "%admin ALL=NOPASSWD:ALL" >> /etc/sudoers
RUN groupadd -f admin
RUN useradd -m -d /home/kozmic -G admin -s /bin/bash kozmic
