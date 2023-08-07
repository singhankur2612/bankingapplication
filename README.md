# bankingapplication

kafka start-
Start Zookeeper: zookeeper-server-start /opt/homebrew/etc/kafka/zookeeper.properties
Start Kafka: kafka-server-start /opt/homebrew/etc/kafka/server.properties
create kafka topic -kafka-topics --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic foobar
