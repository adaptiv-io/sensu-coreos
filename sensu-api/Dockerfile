FROM upfluence/sensu-base:latest
MAINTAINER Alexis Montagne <alexis.montagne@gmail.com>

ENV API_PORT 3000

CMD etcdenv -n $SENSU_NAMESPACE -s http://172.17.42.1:4001 \
  /sensu/bin/sensu-api -v
