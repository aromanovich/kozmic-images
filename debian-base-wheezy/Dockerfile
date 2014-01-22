FROM debian:wheezy
RUN apt-get update -y
RUN apt-get install -y sudo git openssh-client bash apt-utils dialog
RUN echo "%admin ALL=NOPASSWD:ALL" >> /etc/sudoers
RUN groupadd -f admin
RUN useradd -m -d /home/kozmic -G admin -s /bin/bash kozmic
