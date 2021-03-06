# MQ JAVA HTTP SDK

Alyun MQ Documents: http://www.aliyun.com/product/ons

Aliyun MQ Console: https://ons.console.aliyun.com

## Use

### Add Maven Dependency
```
<dependency>
    <groupId>com.aliyun.mq</groupId>
    <artifactId>mq-http-sdk</artifactId>
    <version>1.0.0</version>
</dependency>
```

Or With-dependencies
```
<dependency>
    <groupId>com.aliyun.mq</groupId>
    <artifactId>mq-http-sdk</artifactId>
    <version>1.0.0</version>
    <classifier>jar-with-dependencies</classifier>
</dependency>
```

### Sample

#### V1.0.0 Samples
[Publish Message](https://github.com/aliyunmq/mq-http-samples/blob/master/java/src/main/java/Producer.java)

[Consume Message](https://github.com/aliyunmq/mq-http-samples/blob/master/java/src/main/java/Consumer.java)

#### V1.0.1 Samples
[Publish Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/java/src/main/java/Producer.java)

[Consume Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/java/src/main/java/Consumer.java)

[Transaction Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/java/src/main/java/TransProducer.java)

Note for 1.0.1: Http consumer only support timer msg(less than 3 days), no matter the msg is produced from http or tcp protocal.
