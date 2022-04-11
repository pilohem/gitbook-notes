# Docker Compose and Locust

These two tools are applied in the Week 2 Ungraded [Lab 3](https://github.com/https-deeplearning-ai/machine-learning-engineering-for-production-public/blob/main/course4/week2-ungraded-labs/C4\_W2\_Lab\_3\_Latency\_Test\_Compose/README.md) to test ML application latency and perform load tests on servers.

{% hint style="info" %}
[Docker Compose](https://docs.docker.com/compose/) is a tool for defining and running multi-container Docker applications. With Compose, you use a **YAML** file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.
{% endhint %}

Docker compose is a great option when you need to spin and link different containers.

{% hint style="info" %}
[Locust](https://locust.io)

Used to test server limitations and simulate real-life cases before launching a model into production.

Simulates lots of requests so you can measure model latency, average response time, and throughput (RPS - requests per second)

&#x20;
{% endhint %}
