---
title: "HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs"
collection: publications
permalink: /publication/2024-10-HyperBlocker
date: OCT 1, 2025
venue: 'The 51th International Conference on Very Large Data Bases (VLDB), 2025.'
paperurl: ''
citation: '<strong>Xiaoke Zhu</strong>, Min Xie, Ting Deng, and Qi Zhang. HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs, PVLDB, 18, x, x.'
---
[<font color='#0000FF'>(Download publication here)</font>](https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf)
[<font color='#0000FF'>(Download slides here)</font>]()
[<font color='#0000FF'>(Download source code here)</font>](https://github.com/SICS-Fundamental-Research-Center/HyperBlocker)

### Abstract

This paper studies rule-based blocking in Entity Resolution (ER). We propose HyperBlocker, a GPU-accelerated system for blocking in ER. As opposed to previous blocking algorithms and parallel blocking solvers, HyperBlocker employs a pipelined architecture to overlap data transfer and GPU operations, and improve parallelism by effectively collaborating GPUs and CPUs. It also generates a data-aware and rule-aware execution plan on CPUs, for specifying how rules are evaluated in blocking. Moreover, it develops a variety of hardware-aware optimization and scheduling strategies to achieve massive parallelism and workload balancing across multiple GPUs. Using real-life and synthetic datasets, we show that HyperBlocker is at least 6.1× and 11.2× faster than prior CPU-powered distributed systems and GPU-based ER solvers, respectively. By combining blocking in HyperBlocker with the state-of-the-art ER matchers, we speed up the ER matcher by 26.5x on average with comparable accuracy.