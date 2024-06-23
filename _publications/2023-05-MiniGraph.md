---
title: "MiniGraph: Querying Big Graphs with a Single Machine"
collection: publications
permalink: /publication/2023-05-MiniGraph
date: MAY 1, 2023
venue: 'The 49th International Conference on Very Large Data Bases (VLDB), 2023.'
paperurl: ''
citation: '*Xiaoke Zhu*, Yang Liu, Shuhao Liu, and Wenfei Fan. 2023. MiniGraph: Querying Big Graphs with a Single Machine. PVLDB. 16, 9, 2172–2185.'
---

[(Download publication here)](https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf)
[(Download slides here)](https://hsiaoko.github.io/files/slides/MiniGraph_VLDB2023.pdf)
[(Download source code here)](https://github.com/SICS-Fundamental-Research-Center/MiniGraph)

### Abstract

This paper presents MiniGraph, an out-of-core system for querying big graphs with a single machine. As opposed to previous single-machine graph systems, MiniGraph proposes a pipelined architecture to overlap I/O and CPU operations, and improves multi-core parallelism. It also introduces a hybrid model to support both vertex-centric and graph-centric parallel computations, to simplify parallel graph programming, speed up beyond-neighborhood computations, and parallelize computations within each subgraph. The model induces a two-level parallel execution model to explore both inter-subgraph and intra-subgraph parallelism. Moreover, MiniGraph develops new optimization techniques under its architecture. Using real-life graphs of different types, we show that MiniGraph is up to 76.1x faster than prior out-of-core systems, and performs better than some multi-machine systems that use up to 12 machines.