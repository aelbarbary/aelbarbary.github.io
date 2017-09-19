---
layout: post
title: Kinesis or Kafka ?
---

<!-- ![_config.yml]({{ site.baseurl }}/images/config.png) -->

### Setup and Configuration.

![_config.yml]({{ site.baseurl }}/images/simple.png)

Kafka is an open source streaming platform that you have to host it and configure it yourself. Makes it a little bit complex to manage and configure but gives you more control and better performance.

Kinesis is a a fully-managed streaming processing service that’s available on AWS. The only options you need to configure is number of shards and the number of days you need to keep the data.

### Cost:
![_config.yml]({{ site.baseurl }}/images/cost.png)

Apache Kafka requires that you do all the setup and configuration yourself. There will learning curve at the beginning and it will take some time to tune the platform for your use case.

Kinesis is a cloud service. Thus, the cost for setup and configuration is fairly less but it won't be very efficient for certain use cases on the long run.

### Performance:
![_config.yml]({{ site.baseurl }}/images/fast.png)

Kafka's performance is better given the same price. The reason behind this is that Kinesis needs to write each message synchronously to 3 different machines (availability zones) and this is costly in terms of latency and throughput.

### Maximum Retain Period:
![_config.yml]({{ site.baseurl }}/images/retain.png)

Kafka can store records forever (In Fact, there is nothing called "forever" on planet earth. but you got what I mean. right?).

On the other hand, An Kinesis stream stores records from 24 hours by default, up to 168 hours (7 days only).

### Powered By:
![_config.yml]({{ site.baseurl }}/images/customers.png)

Kafka: linkedin, pinterest, yahoo, spotify, netflex, tumblr, paypal .... and
[more](https://kafka.apache.org/powered-by)

Kinesis: Nordstrom, dash, supercell, NDN ... and [more](https://aws.amazon.com/kinesis/streams/)



<!-- The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub. -->
