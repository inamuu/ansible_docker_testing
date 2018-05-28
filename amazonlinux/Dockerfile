FROM amazonlinux:latest

RUN yum -y reinstall glibc-common
ENV LANG ja_JP.UTF-8

RUN yum -y install \
        vim \
        which \
        ;\
        yum clean all

CMD ["/bin/bash"]
