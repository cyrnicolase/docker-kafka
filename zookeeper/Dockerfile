FROM centos:latest

RUN cd /opt \
    && curl https://downloads.apache.org/zookeeper/zookeeper-3.6.2/apache-zookeeper-3.6.2-bin.tar.gz -o apache-zookeeper-3.6.2-bin.tar.gz \
    && tar -zxvf apache-zookeeper-3.6.2-bin.tar.gz \
    && rm apache-zookeeper-3.6.2-bin.tar.gz \
    && mv apache-zookeeper-3.6.2-bin /zookeeper \
    && yum install -y java-1.8.0 \
    && yum clean all

