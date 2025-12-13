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
    ul li { margin-bottom: 10px; }
</style>

I have served as the designer and/or main developer of the following system projects.

<p><h2>Hetu</h2></p>

<figure align="center">
<img src='../img/hetu_logo-1400.webp' alt='hetu' style="width:20em;"/>
</figure>

<p>
<a href="https://github.com/PKU-DAIR/Hetu">Hetu</a> is a high-performance distributed deep learning system targeting large-scale DL model training, developed and open-sourced by <a href="https://cuibinpku.github.io/">DAIR Lab</a> at Peking University. Attributed to our innovative HSPMD tensor annotations, Hetu flexibly supports the automatic and efficient deployment and training of various DL models (e.g., NLP, vision, multi-modal) over distributed GPU servers. Hetu is further optimized for complex training scenarios where heterogeneity and dynamicity exist, provisioing significant speedup compared to Megatron and DeepSpeed. Discover more in our <a href="https://arxiv.org/pdf/2504.20490">white paper</a>.
</p>

<p>
We welcome everyone interested in the design, development, and optimization of DL systems to contribute codes, create issues or pull requests. Please refer to <a href="https://github.com/PKU-DAIR/Hetu/blob/main/CONTRIBUTING.md">Hetu Contribution Guide</a> for more details.
</p>

<br>

<p><h2>Galvatron</h2></p>

<figure align="center">
<img src='../img/Galvatron.png' alt='galvatron' style="width:20em;"/>
</figure>

<p>
<a href="https://github.com/PKU-DAIR/Hetu-Galvatron">Galvatron</a> is a PyTorch-native, open-source framework for the efficient distributed training of large-scale Transformer models, with specialized optimizations for automatic hybrid parallelism strategies. Given a Transformer model, Galvatron first profiles and analyzes the model execution workload characteristics, creating a precise cost model. Then, Galvatron uses decision trees and dynamic programming to automatically deduce the best combination of parallelism dimensions for each model layer, covering data, tensor, pipeline, sharded data, sequence parallelism, and recomputation. Finally, Galvatron leverages PyTorch features like FSDP and checkpointing to deploy and train the model, seamlessly supporting various accelerators like NVIDIA GPUs and Ascend NPUs. As an open-source project with comprehensive documentation, Galvatron is designed to be user-friendly, enabling easy integration with minimal code changes. Discover more in our <a href="https://arxiv.org/pdf/2504.21411">white paper</a>.
</p>

<p>
We welcome everyone interested in efficient and ease-of-use training of large-scale Transformer models to contribute codes, create issues or pull requests. Please refer to <a href="https://github.com/PKU-DAIR/Hetu-Galvatron/blob/main/CONTRIBUTING.md">Galvatron Contribution Guide</a> for more details.
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
