---
description: Some notes I took when completing the course
---

# 😎 Course 4 Notes

#### How to move a model to Production (model serving)?

* Docker - Installing [TensorFlow Serving](https://www.tensorflow.org/tfx/guide/serving)
* Cloud Platform (GCP, Amazon, Azure)
* TensorFlow Serving via binary installation - without Docker

docker is composed by {dockerfile, dockerimage, dockercontainer}

You can use TensorFLow Serving by:

```
1. Using docker container
2. using TF serving directly 	
```

Quiz

What is the advantage of using the **TensorFlow-model-server-universal** binary to install TensorFlow Serving over the **TensorFlow-model-server** binary?

* <mark style="color:green;">**The universal binary works on most of the machines.**</mark>
* The universal binary is a fully optimized server.
* The universal binary includes platform-specific instruction sets.

More information on using TF Serving [here](https://www.tensorflow.org/tfx/tutorials/serving/rest\_simple).&#x20;

{% hint style="info" %}
<mark style="background-color:orange;">If you have troubles reading commands with Linux terminal you can read more about</mark> [<mark style="background-color:orange;">curl</mark>](https://linuxize.com/post/curl-command-examples/) <mark style="background-color:orange;">and</mark> [<mark style="background-color:orange;">piping</mark>](https://www.geeksforgeeks.org/piping-in-unix-or-linux/)<mark style="background-color:orange;">.</mark>
{% endhint %}

#### Important Metrics when serving a model

* Latency
* Throughput: Number of successful requests served per unit time
* :moneybag:Cost

![Source: http://deeplearning.ai/](<.gitbook/assets/image (2).png>)

#### Example of application (Airline Recommendation Service)

How does the three metrics relate each other?

![Source: http://deeplearning.ai/](<.gitbook/assets/image (5).png>)

