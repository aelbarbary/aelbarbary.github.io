---
layout: post
title: Software Scalability ... Inspiration from God's creations
comments: true
---

![_config.yml]({{ site.baseurl }}/images/scalability.png)

> So blessed is Allah, the best of creators _Al-Muminoon-14_

### Best Practices

* Offload the database by caching and minimizing network traffic.
* Co-Location: put things close to where they are supposed to be delivered
* Minimize resource contentions
* Asynchronous processing: separates requests from actual processing
* Minimize network chatter
* SWIM LANES: Create fault isolated “swim lanes” of hardware by customer segmentation. This prevents problems with one customer from causing issues across all customers. This also helps with diagnosis of issues and code roll outs.
* MONITORING
* REPLICATION
* SHARDING
* Small ROLL: Roll out new code versions slowly
* LOAD & PERFORMANCE TESTING
* ROLLBACK
