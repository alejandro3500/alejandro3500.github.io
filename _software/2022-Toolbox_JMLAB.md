---
title: "Toolbox: Adhesive bonding optimization (2022)"
excerpt: ""
collection: portfolio
---

The JMLab Toolbox for Multi-objective Optimization with Stochastic Kriging (MOSK) is a comprehensive tool designed to streamline the process of designing experiments, managing measurement data, and performing multi-objective optimization with noisy outcomes under feasibility constraints. Users can generate a Design of Experiments (DoE), download it for external measurements, and upload the resulting data for validation and integration with the current dataset. The toolbox supports optional simulations through the JMLab simulator and allows flexible configuration of the optimization process, including choice of covariance function, feasibility classifier, and acquisition function optimizer. It generates query points that represent suggested new samples for optimization, displaying them in a sortable table along with their scalarized objectives and feasibility probabilities, and provides visualization of the Pareto front when simulations are performed. Users can download the updated dataset or query points, manage uploaded data, and control whether duplicate points are displayed, making it a complete workflow for iterative multi-objective optimization.

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/JMLabToolbox_component_diagram.png" alt="JMLabToolbox_DC" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Component diagram of the JMLab Toolbox
  </figcaption>
</figure>

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/JMLabToolbox_DOE.png" alt="JMLabToolbox_DC" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Design of experiments
  </figcaption>
</figure>

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/JMLabToolbox_LoadData.png" alt="JMLabToolbox_LD" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Loading experiments
  </figcaption>
</figure>

<figure style="float: left; margin: 0 0 10px 10px; width: 500px;">
  <img src="../../images/JMLabToolbox_Optimization.png" alt="JMLabToolbox_Opt" style="width: 100%;">
  <figcaption style="font-size: 0.9em; text-align: center;">
    Obtaining new sampling points for the experts
  </figcaption>
</figure>
