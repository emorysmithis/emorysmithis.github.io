---
title: "Concurrent graph queries on the Lucata Pathfinder"
collection: publications
category: manuscripts
permalink: /publication/2022-09-23-concurrent-graph-queries-on-the-lucata-pathfinder-2
date: 2022-09-23
paperurl: 'https://arxiv.org/abs/2209.11889'
citation: 'E. Smith, S. Kuntz, J. Riedy, and M. Deneroff, “Concurrent graph queries on the Lucata Pathfinder,” arXiv preprint arXiv:2209.11889, 2022.'
---

High-performance analysis of unstructured data like graphs now is critical for applications ranging from business intelligence to genome analysis. Towards this, data centers hold large graphs in memory to serve multiple concurrent queries from different users. Even a single analysis often explores multiple options. Current computing architectures often are not the most time- or energy-efficient solutions. The novel Lucata Pathfinder architecture tackles this problem, combining migratory threads for low-latency reading with memory-side processing for high-performance accumulation. One hundred to 750 concurrent breadth-first searches (BFS) all achieve end-to-end speed-ups of 81% to 97% over one-at-a-time queries on a graph with 522M edges. Comparing to RedisGraph running on a large Intel-based server, the Pathfinder achieves a 19 speed-up running 128 BFS queries concurrently. The Pathfinder also efficiently supports a mix of concurrent analyses, demonstrated with connected components and BFS.