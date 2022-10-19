FROM influxdb:1.8

LABEL description="InfluxDB docker image"

USER root

ADD influxdb.template.conf /influxdb.template.conf

ADD run.sh /run.sh
RUN chmod +x /run.sh

CMD ["/run.sh"]

