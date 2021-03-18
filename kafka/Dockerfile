FROM centos:latest

RUN cd /opt \
    && curl https://downloads.apache.org/kafka/2.7.0/kafka_2.13-2.7.0.tgz -o kafka_2.13-2.7.0.tgz \
    && tar -zxvf kafka_2.13-2.7.0.tgz \
    && rm kafka_2.13-2.7.0.tgz \
    && mv kafka_2.13-2.7.0 /kafka \
    && yum install -y java-1.8.0 \
    && yum clean all


