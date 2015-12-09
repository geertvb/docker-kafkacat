# docker-kafkacat

Docker container for running kafkacat

# Download

    docker pull geertvb/kafkacat

# Example

Consume topic "log-test" from kafka server 192.168.99.100:9092

    docker run -t -i --rm geertvb/kafkacat kafkacat -C -b 192.168.99.100:9092 -t log-test