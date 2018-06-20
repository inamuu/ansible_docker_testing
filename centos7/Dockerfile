FROM centos:7

RUN yum -y reinstall glibc-common
ENV LANG ja_JP.UTF-8

RUN yum -y install \
        vim \
        which \
        python \
        ;\
        yum clean all

RUN ln -sf /usr/share/zoneinfo/Japan /etc/localtime

CMD ["/bin/bash"]
