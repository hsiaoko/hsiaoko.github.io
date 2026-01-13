---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
<script src="bootstrap/js/bootstrap.bundle.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    :root {
      font-size: 16px; /* 默认16px，改为18px（所有rem单位会按比例缩放） */
    }
</style>

## Conference papers
** indicates that author names or major contributors are listed in alphabetical order.
You can also find my articles on <u><a href="https://scholar.google.com/citations?user=Zu3XLB8AAAAJ&hl=en">my Google Scholar profile</a>.</u>

### 2026
<ul>   
  <li>
    <p>
      Wenfei Fan, Yixuan Luo, Ping Lu, <b>Xiaoke Zhu**</b>, <br />
      <em>Enumerating Graph Pattern Matches with ML Oracles,</em> <br />
      The 2026 ACM Conference on Management of Data (SIGMOD 2026) 
      <a href="https://hsiaoko.github.io/files/paper/NPML_paper.pdf">[Paper]</a>
    </p>
  </li>
</ul>


### 2025

<ul>   
  <li>
    <p>
      Wenchao Bai, Wenfei Fan, Shuhao Liu, Kehan Pang, <b>Xiaoke Zhu**</b>, Jiahui Jin, <br />
      <em>GPU-Accelerated Graph Cleaning with a Single Machine,</em> <br />
      The 2025 ACM Conference on Management of Data (SIGMOD 2025) 
      <a href="https://hsiaoko.github.io/files/paper/MiniClean_paper.pdf">[Paper]</a>
    </p>
  </li>
</ul>

<ul>   
  <li>
    <p>
      Yang Liu, Wenfei Fan, Shuhao Liu, <b>Xiaoke Zhu</b>, Jianxin Li, <br />
      <em>A Single Machine System for Querying Big Graphs with PRAM,</em> <br />
      The 51th International Conference on Very Large Data Bases (VLDB 2025)
      <a href="https://hsiaoko.github.io/files/paper/Planar_paper.pdf">[Paper]</a>
      <a href="https://github.com/SICS-Fundamental-Research-Center/graph-systems">[Source Code]</a>
    </p>
  </li>
</ul>

<ul>   
  <li>
    <p>
      <b>Xiaoke Zhu</b>, Min Xie, Ting Deng, Qi Zhang, <br />
      <em>HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs,</em> <br />
      The 51th International Conference on Very Large Data Bases (VLDB 2025) 
      <a href="https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf">[Paper]</a>
      <a href="https://github.com/SICS-Fundamental-Research-Center/HyperBlocker">[Source Code]</a>
      <a href="https://hsiaoko.github.io/files/slides/HyperBlocker_slides_VLDB_2025.pdf">[Slides]</a>
    </p>
  </li>
</ul>

### 2024

<ul>   
  <li>
    <p>
      <b>Xiaoke Zhu</b>, Qi Zhang, Wei Zhou and Ling Liu, <br />
      <em>Deep Learning Service for Efficient Data Distribution Aware Sorting,</em> <br />
      The 12th International Conference on Big Data (BigData 2024) 
      <a href="https://hsiaoko.github.io/files/paper/NN-sort_paper.pdf">[Paper]</a>
      <a href="https://hsiaoko.github.io/files/slides/NN-sort_slides_BigData_2024.pdf">[Slides]</a>
    </p>
  </li>
</ul>

### 2023

<ul>   
  <li>
    <p>
      <b>Xiaoke Zhu</b>, Yang Liu, Shuhao Liu, and Wenfei Fan, <br />
      <em>MiniGraph: Querying Big Graphs with a Single Machine,</em><br />
      The 49th International Conference on Very Large Data Bases (VLDB 2023) 
      <a href="https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf">[Paper]</a>
      <a href="https://github.com/SICS-Fundamental-Research-Center/MiniGraph">[Source Code]</a>
      <a href="https://hsiaoko.github.io/files/slides/MiniGraph_slides_VLDB_2023.pdf">[Slides]</a>
    </p>
  </li>
</ul>

### 2022

<ul>   
  <li>
    <p>
      Ting Deng, Wenfei Fan, Ping Lu, Xiaomeng Luo, <b>Xiaoke Zhu**</b>, and Wanhe An, <br />
      <em>Deep and collective entity resolution in parallel,</em><br />
      The 38th International Conference on Data Engineering (ICDE 2022)
      <a href="https://hsiaoko.github.io/files/paper/PER_paper.pdf">[Paper]</a>
      <a href="https://hsiaoko.github.io/files/slides/PER-slides-5min-0510.pdf">[Slides]</a>
    </p>
  </li>
</ul>

### 2021

<ul>   
  <li>
    <p>
      <b>Xiaoke Zhu</b>, Qi Zhang, Taining Cheng, Ling Liu, Wei Zhou, and Jing He, <br />
      <em>DLB: Deep Learning Based Load Balancing,</em><br />
      The 14th International Conference on Cloud Computing (CLOUD 2021)
      <a href="https://hsiaoko.github.io/files/paper/DLB_paper.pdf">[Paper]</a>
      <a href="https://github.com/hsiaoko/DLB-CLOUD-2021">[Source Code]</a>
    </p>
  </li>
</ul>

## PhD Dissertation

### Research on Eﬃcient Large-Scale Graph Data Querying Technologies for Single-Machine Systems
A thesis submitted for the Degree of Doctor of Philosophy to the Beihang Univeristy.

### Abstract
Graph query, a specialized method for querying graph-structured data, is widely used in areas such as social network analysis, knowledge graph construction, and Web graph mining. To handle massive graph data, various parallel graph query systems have been proposed in both academia and industry. Existing solutions often rely on distributed clusters to support processing at an ultra-large scale, but their high deployment and maintenance costs limit their adoption primarily to large enterprises. In the Chinese market, although small and medium-sized enterprises (SMEs) have a significant need for efficient graph querying, their limited IT budgets make it difficult to implement such applications. To address this, single-machine-based graph query systems have gradually emerged. With the rapid development of hardware acceleration technologies such as GPUs in recent years, modern single-machine systems have demonstrated processing potential that approaches or even rivals that of distributed clusters.

Despite the potential of single-machine graph query systems, they face four challenges:

(1) Programming Model Limitations: Current vertex-centric and graph-centric models present a trade-off: while vertex-centric enables simple programming but suffers from communication overhead, graph-centric supports global operations but leads to computational fragmentation when parallelized. The key challenge is achieving both simplicity and efficiency.

(2) I/O Bottleneck: Processing graphs larger than memory causes frequent data swapping, leading to significant I/O overhead and query latency. The challenge is to minimize data exchange while maximizing resource utilization, enabling single-machine performance to rival distributed clusters.

(3) GPU Acceleration Limitations: Although GPU acceleration addresses CPU parallelism constraints, architectural differences and graph data irregularity cause load imbalance and low utilization. The challenge is designing a hybrid scheduling scheme that adapts to both graph query patterns and GPU architecture.

(4) Domain-Specific Optimization: General-purpose systems underperform in complex scenarios like graph entity recognition, which requires simultaneous pattern matching and semantic computation. The challenge is designing deeply customized architectures tailored to specific computational needs and performance goals.

This research tackles performance optimization in single-machine graph query systems by introducing novel solutions to key challenges in programming models, external storage I/O, GPU acceleration, and domain-specific optimization. The main contributions are as follows:

We propose a hybrid graph-centric/vertex-centric programming model that combines global processing capabilities with fine-grained computation. A two-level parallel architecture is introduced, implementing subgraph-level parallelism to eliminate hop-by-hop communication overhead at the coarse-grained level, and vertex-level parallelism to improve computational efficiency at the fine-grained level.

We design a pipelined external storage architecture that employs asynchronous pipelining and intelligent task scheduling to minimize memory-storage swapping latency, improve resource utilization, and reduce redundant data transfer. Evaluation shows a 76 times performance gain over state-of-the-art external storage graph query systems, effectively overcoming I/O bottlenecks.

We develop a GPU-aware hybrid task scheduling scheme that integrates static pre-partitioning with dynamic scheduling to handle irregular memory access and load imbalance in graph queries. The approach achieves a 12.7 times speedup over existing GPU-based systems while significantly improving resource utilization.

We present a specialized acceleration framework for graph entity recognition, integrating a heterogeneous computing architecture with a rule-data dual-aware optimization engine. The framework employs pipelined processing, GPU-customized kernels, and multi-device coordination for full-process acceleration, along with dynamic cost-based execution planning. It outperforms general-purpose graph query systems by over 9 times.

<a href="https://hsiaoko.github.io/files/slides/Thesis-slides.pdf">[Download slides here]</a>