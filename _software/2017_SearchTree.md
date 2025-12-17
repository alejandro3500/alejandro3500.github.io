---
title: "Data structure project: Implementation of a file search engine using Splay Trees (2017)"
excerpt: ""
collection: portfolio
---

This projects study the splay trees as a self adjusting binary search tree data structure, covering their theoretical foundations, amortized time complexity, and practical implementation. The work explains the principles of splaying through rotations, analyzes performance using amortized analysis based on the credit invariant method, and demonstrates that sequences of operations achieve logarithmic amortized complexity. A generic implementation of splay trees is developed using linked nodes, detailing insertion, deletion, search, and rotation algorithms. To illustrate their practical usefulness, the study applies splay trees to the implementation of a file search tool with a cache mechanism, where frequently accessed search patterns are optimized for faster retrieval. The results highlight the suitability of splay trees for applications that benefit from locality of reference, as well as their simplicity, memory efficiency, and adaptability compared to other self balancing tree structures.

Collaborators: Claudia Fernández, Humberto López, Ariel Alba


<figure style="float: left; margin: 0 0 10px 10px; width: 700px;">
  <img src="../../images/Searcher_tree.png" alt="splay_tree" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Main UI of the file search engine implemented with Splay Trees
  </figcaption>
</figure>
