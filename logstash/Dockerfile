FROM centos:6.9
RUN yum install java -y
ADD logstash-5.6.3.tar.gz /root/
COPY logstash.conf /root/
WORKDIR /root/logstash-5.6.3/bin/
CMD ./logstash -f /root/logstash.conf


