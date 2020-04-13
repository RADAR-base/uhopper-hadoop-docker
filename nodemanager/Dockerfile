ARG HADOOP_TAG
FROM radarbase/k8s-hadoop:${HADOOP_TAG}

ADD run.sh /run.sh
RUN chmod a+x /run.sh

CMD ["/run.sh"]
