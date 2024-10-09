---
title: "HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs"
collection: publications
permalink: /publication/2024-10-HyperBlocker
date: OCT 1, 2025
venue: 'The 51th International Conference on Very Large Data Bases (VLDB).'
paperurl: ''
citation: '<strong>Xiaoke Zhu</strong>, Min Xie, Ting Deng, and Qi Zhang. MiniGraph: Querying Big Graphs with a Single Machine. PVLDB. 18, x, x-x.'
---

[<font color='#0000FF'>(Download publication here)</font>](https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf)
[<font color='#0000FF'>(Download slides here)</font>](https://hsiaoko.github.io/files/slides/HyperBlocker_VLDB2023.pdf)
[<font color='#0000FF'>(Download source code here)</font>](https://github.com/SICS-Fundamental-Research-Center/HyperBlocker)

### Abstract

This paper studies rule-based blocking in Entity Resolution (ER). We propose HyperBlocker, a GPU-accelerated system for blocking in ER. As opposed to previous blocking algorithms and parallel blocking solvers, HyperBlocker employs a pipelined architecture to overlap data transfer and GPU operations. It generates a data- aware and rule-aware execution plan on CPUs, for specifying how rules are evaluated, and develops a number of hardware-aware optimizations to achieve massive parallelism on GPUs. Using real- life datasets, we show that HyperBlocker is at least 6.8× and 9.1× faster than prior CPU-powered distributed systems and GPU-based ER solvers, respectively. Better still, by combining HyperBlocker with the state-of-the-art ER matcher, we can speed up the overall ER process by at least 30% with comparable accuracy.