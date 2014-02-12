FROM kozmic/ubuntu-base:12.04
RUN apt-get update -y
RUN apt-get install -y python python-dev python-pip
RUN apt-get install -y mysql-server mysql-client libmysqlclient-dev
ADD ./files/my.cnf /etc/mysql/conf.d/my.cnf
# TODO Add more languages and databases.
