---
title: "Genpro - An Intelligent Software Framework for Genetic Inference Using Logic Programming (2013)"
excerpt: ""
collection: portfolio
---

This work focuses on the design and implementation of an intelligent software system for genetic analysis, based on logical reasoning and symbolic inference. The system leverages the inference mechanisms of Prolog, a declarative logic programming language, to model, analyze, and reason about phenotypic disease expression within family pedigrees, with the objective of inferring the underlying patterns of genetic inheritance.

The project started with a structured analysis of the theoretical foundations required to determine inheritance patterns, including dominance relationships across generations and the mechanisms by which genetic traits are transmitted to offspring. This theoretical grounding informs the formalization of domain knowledge into a logic-based representation that supports efficient automated reasoning. Based on an extensive review of the relevant literature, a knowledge representation strategy is defined that balances expressiveness, computational efficiency, and interpretability, enabling the system to derive accurate conclusions while remaining transparent and easy to maintain.

<figure style="float: left; margin: 0 10px 10px 10px; width: 500px;">
  <img src="../../images/Genetic_familyTree.png" alt="FamilyTree" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Family tree representation. (a) Original Tree (b) Genpro implementation
  </figcaption>
</figure>

The resulting intelligent system integrates symbolic reasoning (through prolog) with a user-oriented software design. A graphical user interface (Java) is provided to facilitate interaction with the underlying reasoning engine, allowing users to input family data, trigger inference processes, and interpret the results. A concise user manual describes the system’s functionality from an end-user perspective, emphasizing usability and clarity. The knowledge base and inference mechanisms were validated using multiple family trees drawn from Medical Genetics coursework. In all evaluated cases, the system correctly identified the expected inheritance patterns, demonstrating the robustness and reliability of the proposed intelligent software approach.

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/genpro_main_window.png" alt="Genpro" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Main window - Genpro
  </figcaption>
</figure>

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/Genpro_drawingtree.png" alt="Genpro_drawingtree" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Drawing a family tree in Genpro
  </figcaption>
</figure>
