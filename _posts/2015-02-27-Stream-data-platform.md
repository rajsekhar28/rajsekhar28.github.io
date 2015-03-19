---
layout : post
title : Stream data platform
---

In this post, I'll explain Stream data platform. Please note that some of the below data points are taken from [confluent blog](http://blog.confluent.io/2015/02/25/stream-data-platform-1/) 

Stream data platform has 2 primary uses:

1. Data integration
2. Stream processing

Key requirements of a stream data platform

1. handle critical updates eg. Replication
2. support high throughput
3. low latency 
4. can store data for longer periods
5. can be integrated with stream processing systems
6. can interact with lots of services

### Stream processing ###

Prominent Stream processing frameworks are Samza, Storm or Spark.

#### Kafka ####

Things to keep in mind

1. Limit the number of clusters. For eg. have one cluster in a region
2. Using single data format


