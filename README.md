# Getting Started

### Prerequisite


You need to have maven environment (mvn), java version 11, active mq

## Link download active mq:
### https://activemq.apache.org/components/classic/download/


### Steps

1. The above application into the package jar. Run command: mvn clean install
2. Open 2 console and run command:

- java -cp target/demo-active-mq-1.0-SNAPSHOT.jar com.nguyenduc.consumer.Consumer Queue


- java -cp target/demo-active-mq-1.0-SNAPSHOT.jar com.nguyenduc.producer.Producer Queue

