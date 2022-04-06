Variables need to be passed are 
A. /opt/kafka/config/server.properties parameters
1. broker_id=<broker_id(number)> 
2. zookeeper=<zookeeper_connec_url>

B. /opt/kafka/bin/kafka-server-start.sh HEAP size

1. kafka_heap=<HEAP_SIZE>
 e.g. kafka_heap='-Xmx16G -Xms4G'  