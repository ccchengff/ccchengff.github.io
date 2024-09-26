---
title: "System Projects"
draft: false
menu:
  main:
    name: "Projects"
    weight: 10
---

{{< rawhtml >}}

<style>
    ul li { margin-bottom: 15px; }
</style>

I have served as the designer and/or main developer of the following system projects.

<p><h2>Hetu</h2></p>

<figure align="center">
<img src='../img/hetu_logo-1400.webp' alt='hetu' style="width:20em;"/>
</figure>

<p>
<a href="https://github.com/PKU-DAIR/Hetu">Hetu</a> is a high-performance distributed deep learning system targeting trillions of parameters DL model training, developed and open-sourced by <a href="https://cuibinpku.github.io/">DAIR Lab</a> at Peking University. It takes account of both high availability in industry and innovation in academia, which has a number of advanced characteristics:

<ul>
<li>
Applicability. DL model definition with standard dataflow graph; many basic CPU and GPU operators; efficient implementation of more than plenty of DL models and at least popular 10 ML algorithms.
</li>

<li>
Efficiency. Achieve at least 30% speedup compared to TensorFlow on DNN, CNN, RNN benchmarks.
</li>

<li>
Flexibility. Supporting various parallel training protocols and distributed communication architectures, such as Data/Model/Pipeline parallel; Parameter server & AllReduce.
</li>

<li>
Scalability. Deployment on more than 100 computation nodes; Training giant models with trillions of model parameters, e.g., Criteo Kaggle, Open Graph Benchmark.
</li>

<li>
Agility. Automatically ML pipeline: feature engineering, model selection, hyperparameter search.
</li>
</ul>
</p>

<p>
We welcome everyone interested in machine learning or graph computing to contribute codes, create issues or pull requests. Please refer to <a href="https://github.com/PKU-DAIR/Hetu/blob/main/CONTRIBUTING.md">Hetu Contribution Guide</a> for more details.
</p>

<br>

<p><h2>PowerFL</h2></p>

<figure align="center">
<img src='../img/powerfl.png' alt='powerfl' style="width:20em;"/>
</figure>

<p>
PowerFL is an industrial-grade federated privacy-enhancing computing system for geo-distributed collaboration. It concentrates on the federated machine/deep learning and secure collaborative data analysis among enterprises/organizations, with a number of advantageous characteristics:

<ul>

<li>
Security. PowerFL offers a variety of robust privacy protection mechanisms, including homomorphic encryption, secret sharing, differential privacy, and oblivious transfer, meeting financial-grade security requirements. Additionally, PowerFL utilizes a decentralized architectural design, without the need of any trusted third parties or central nodes, fulfilling the security needs of real-world business scenarios.
</li>

<li>
Efficiency. PowerFL enhances communication and computation efficiency through a series of innovations in system architectures, asynchronous computing, communication optimization, and high-performance algorithm optimization.
</li>

<li>
Functionality. PowerFL offers comprehensive full-stack capabilities in privacy-enhancing computation, encompassing a wide range of functions such as collaborative feature engineering algorithms, federated machine/deep learning algorithms, and secure data analysis.
</li>

<li>
Cloud-nativeness. PowerFL adopts a cloud-native design, supporting virtualized deployment and flexible resource scaling based on YARN and Kubernetes, with particular advantages in handling high concurrency and flexible resource scaling.
</li>

</ul>
</p>

<br>

<p><h2>Angel</h2></p>

<figure align="center">
<img src='../img/angel_logo.png' alt='angel' style="width:20em;"/>
</figure>

<p>
<a href="https://github.com/Angel-ML/angel">Angel</a> is a high-performance distributed machine learning and graph computing platform based on the philosophy of Parameter Server. It is tuned for performance with big data from Tencent and has a wide range of applicability and stability, demonstrating increasing advantage in handling higher dimension model. Angel is jointly developed by Tencent and Peking University, taking account of both high availability in industry and innovation in academia.
</p>

<p>
With model-centered core design concept, Angel partitions parameters of complex models into multiple parameter-server nodes, and implements a variety of machine learning algorithms and graph algorithms using efficient model-updating interfaces and functions, as well as flexible consistency model for synchronization. Angel is developed with Java and Scala. It supports running on Yarn. With PS Service abstraction, it supports Spark on Angel. Graph computing and deep learning frameworks support is under development and will be released in the future.
</p>

<p>
We welcome everyone interested in machine learning or graph computing to contribute code, create issues or pull requests. Please refer to <a href="https://github.com/Angel-ML/angel/blob/master/CONTRIBUTING.md"> Angel Contribution Guide</a> for more details.
</p>

{{< /rawhtml >}}
