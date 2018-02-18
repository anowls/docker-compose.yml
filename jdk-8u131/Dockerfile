FROM anowls/sshd:latest

LABEL maintainer=fpky_0729@126.com

ADD ./jdk-8u131-linux-x64.tar.gz /opt

ENV JAVA_HOME=/opt/jdk1.8.0_131 

ENV PATH=$PATH:$JAVA_HOME/bin 

RUN echo "export JAVA_HOME=/opt/jdk1.8.0_131" >> /etc/profile

RUN echo "export PATH=$PATH:$JAVA_HOME/bin" >> /etc/profile
