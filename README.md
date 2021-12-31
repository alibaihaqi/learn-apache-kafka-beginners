# learn-apache-kafka-beginners

This is learning code from Udemy Course for Apache Kafka Series.

Link: [Apache Kafka Series - Learn Apache Kafka for Beginners](https://www.udemy.com/course/apache-kafka/)

## CLI for Apache Kafka (Local Learning)

### Console Consumer
```bash
# Listen for topic w/ group (default Kafka generate random group)
kafka-console-consumer --bootstrap-server localhost:9092 --topic first_topic --group my-first-application 
```

### Consumer Group
```bash
# Check for consumer group
# --describe : is used to get detail information of the group
kafka-consumer-groups --bootstrap-server localhost:9092 --describe --group my-first-application
```

Happy Learning!