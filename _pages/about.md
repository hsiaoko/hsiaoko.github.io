---
permalink: /
title: "About Me"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
<script src="bootstrap/js/bootstrap.bundle.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1.0">



I am Xiaoke Zhu (朱筱可, Hsiaoko Chu in Wade-Giles romanization), 
currently a research fellow at Shenzhen Institute of Computing Sciences (SICS).
In Sep. 2025, I received my Ph.D. degree at [Beihang University](https://ev.buaa.edu.cn/) (BUAA), under the supervision of [Prof. Wenfei Fan](https://homepages.inf.ed.ac.uk/wenfei/). 
Before that, I received master degree at [Yunnan University](http://english.ynu.edu.cn/) (YNU) in 2020, where I was advised by [Prof. Wei Zhou](https://ieeexplore.ieee.org/author/37085625745) and [Prof. Shaowen Yao](https://ieeexplore.ieee.org/author/37402574900).


<!--
<font color=red>
  I am looking for a postdoctoral position. If you are interested, please contact me.  
</font>

<br>
-->

<h2 style="color: black;">News</h2>
<ul style="list-style-type:disc; padding-left: 0; margin-left: 0;height: 400px;overflow: hidden;overflow-y: scroll;"> 
<li><span class="badge bg-success">NOV 2024</span> Our  <a href="https://hsiaoko.github.io/files/paper/MiniClean_paper.pdf">GPU-Accelerated Graph Cleaning with a Single Machine</a> paper was accepted to <b>SIGMOD 2025</b>. </li>
<li><span class="badge bg-success">NOV 2024</span> Our  <a href="https://hsiaoko.github.io/files/paper/Planar_paper.pdf">A Single Machine System for Querying Big Graphs with PRAM</a> paper was accepted to <b>VLDB 2025</b>. </li>
<li><span class="badge bg-success">OCT 2024</span> Our <a href="https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf">HyperBlocker: Accelerating Rule-Based Blocking in Entity Resolution Using GPUs</a> paper was accepted to <b>VLDB 2025</b>. </li>
<li><span class="badge bg-success">OCT 2024</span> Our <a href="https://hsiaoko.github.io/files/paper/NN-sort_paper.pdf">Deep Learning Service for Efficient Data Distribution Aware Sorting</a> paper was accepted to <b>IEEE BigData 2024</b>. </li>
<li><span class="badge bg-success">Apr 2023</span> Our <a href="https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf">MiniGraph: Querying Big Graphs with a Single Machine</a> paper was accepted to <b>VLDB 2023</b>. </li>
<li><span class="badge bg-success">Feb 2022</span> Our <a href="https://hsiaoko.github.io/files/paper/PER_paper.pdf">Deep and Collective Entity Resolution in Parallel</a> paper was accepted to <b>ICDE 2022</b>. </li>
<li><span class="badge bg-success">Sep 2021</span> I joined <a href="https://en.sics.ac.cn">Shenzhen Institute of Computing Science</a> (SICS) as a research intern. </li>
<li><span class="badge bg-success">Jul 2021</span> Our <a href="https://hsiaoko.github.io/files/paper/DLB_paper.pdf">DLB: Deep Learning Based Load Balancing</a> paper was accepted to <b>IEEE CLOUD 2021</b>. </li>
</ul>

# Research Interests
My research focuses on graph computing and databases, optimizing runtime efficiency for shared-memory and CPU/GPU architectures, with publications in SIGMOD, VLDB, ICDE, BigData, and CLOUD. A brief summary of my past work can be found below.

### Graph Computing Systems
I have worked on building a high-level programming model and runtime system that can execute applications on shared-memory or out-of-memory architectures with CPUs or GPUs. For out-of-core graph analytics (e.g., PageRank, SSSP), I improved I/O efficiency, and for graph mining (e.g., Graph Data Cleaning, Pattern Matching), I optimized GPU performance. Relevant results were published in  [[VLDB'23](https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf), [VLDB'25](https://hsiaoko.github.io/files/paper/planar_paper.pdf), [SIGMOD'25](https://hsiaoko.github.io/files/paper/miniclean_paper.pdf)]

### Data Cleaning Systems
I have worked on improving the performance of data cleaning systems on modern hardware like GPU or on distributed cluster. I have also compared different parallel runtime systems for data cleaning, and identified their performance bottlenecks.  Relevant results were published in  [[ICDE'22](https://hsiaoko.github.io/files/paper/PER_paper.pdf), [VLDB'25](https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf), [SIGMOD'25](https://hsiaoko.github.io/files/paper/miniclean_paper.pdf)]

### AI4DB
I have leverages machine learning and deep learning model to improve tasks traditionally handled by  human database administrators or classical algorithms, enabling more efficient data processing and resource management. Specially I have designed learned models for sorting, load balancing, and scheduling. Relevant results were published in  [[CLOUD'21](https://hsiaoko.github.io/files/paper/DLB_paper.pdf), [BigData'24](https://hsiaoko.github.io/files/paper/NN-sort_paper.pdf)]






<!--
# News
* (2024/11) Our [GPU-Accelerated Graph Cleaning with a Single Machine](https://hsiaoko.github.io/files/paper/miniclean_paper.pdf) paper was accepted to **SIGMOD 2025**.
* (2024/11) Our [A Single Machine System for Querying Big Graphs with PRAM](https://hsiaoko.github.io/files/paper/planar_paper.pdf) paper was accepted to **VLDB 2025**.
* (2024/10) Our [Deep Learning Service for Efficient Data Distribution Aware Sorting](https://hsiaoko.github.io/files/paper/NN-sort_paper.pdf) paper was accepted to **BigData 2024**.
* (2024/10) Our [HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs](https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf) paper was accepted to **VLDB 2025**.
* (2023/04) Our [MiniGraph: Querying Big Graphs with a Single Machine](https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf) paper was accepted to **VLDB 2023**.
* (2022/02) Our [Deep and Collective Entity Resolution in Parallel](https://hsiaoko.github.io/files/paper/PER_paper.pdf) paper was accepted to **ICDE 2022**.
* (2021/09) I joined [Shenzhen Institute of Computing Science](https://en.sics.ac.cn) (SICS) as a research intern.
* (2021/07) Our [DLB: Deep Learning Based Load Balancing](https://hsiaoko.github.io/files/paper/DLB_paper.pdf) paper was accepted to **CLOUD 2021**.
* 
# Talks
* "MiniGraph: Querying Big Graphs with a Single Machine"
  * Great Bay Area Digital Tech Workshop, June 2023
  * VLDB conference, September 2023
* "DLB: Deep Learning Based Load Balancing"
  * IEEE CLOUD conference, September 2021


# Professional Services
### External Reviewer
* ICDE'24, ICDE'25

<br/><br/>
-->

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=000000&w=230&t=tt&d=eHHOFbP732DR-cMe1ytaYJxII5gJ_ocpixMhAWlufLU&co=ffffff&ct=0a0909&cmn=00fff0&cmo=f3cefc'></script>

