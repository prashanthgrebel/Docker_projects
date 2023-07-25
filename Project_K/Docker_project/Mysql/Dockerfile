FROM centos:7
RUN yum install epel-release vim net-tools wget sysstat stat psmisc utils.pm yum-utils -y
RUN yum update -y
RUN wget https://repo.mysql.com/mysql80-community-release-el7-1.noarch.rpm\
    rpm -ivh mysql80-community-release-el7-1.noarch.rpm
RUN systemctl enable mysqld

CMD [ "/usr/sbin/inti" ]