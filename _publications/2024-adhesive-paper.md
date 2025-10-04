---
title: "Bayesian multi-objective optimization of process design parameters in constrained settings with noise: an engineering design applications"
collection: publications
category: manuscripts
permalink: /publication/2024-adhesive-paper
excerpt: 'This study applies advanced learning and Bayesian optimization to efficiently identify Pareto-optimal adhesive bonding process parameters under multiple noisy objectives and strict experimental constraints, reducing the need for costly physical testing.'
date: 2024-01-10
venue: 'Engineering with computers'
bibtexurl: '../files/adhesive_bibtex.bib'
paperurl: 'https://doi.org/10.1007/s00366-023-01922-8'
citation: 'Morales-Hernández, A., Rojas Gonzalez, S., Van Nieuwenhuyse, I. et al. (2024). &quot;Bayesian multi-objective optimization of process design parameters in constrained settings with noise: an engineering design application.&quot; <i>Engineering with Computers</i>. 40.'
---

The use of adhesive joints in various industrial applications has become increasingly popular due to their beneficial characteristics, including their high strength-to-weight ratio, design flexibility, limited stress concentrations, planar force transfer, good damage tolerance, and fatigue resistance. However, finding the best process parameters for adhesive bonding can be challenging. This optimization problem is inherently multi-objective, aiming to maximize break strength while minimizing cost and constrained to avoid any visual damage to the materials and ensure that stress tests do not result in adhesion-related failures. Additionally, testing the same process parameters several times may yield different break strengths, making the optimization process uncertain. Conducting physical experiments in a laboratory setting is costly, and traditional evolutionary approaches like genetic algorithms are not suitable due to the large number of experiments required for evaluation. Bayesian optimization is suitable in this context, but few methods simultaneously consider the optimization of multiple noisy objectives and constraints. This study successfully applies advanced learning techniques to emulate the objective and constraint functions based on limited experimental data. These are incorporated into a Bayesian optimization framework, which efficiently detects Pareto-optimal process configurations under strict budget constraints.
