---
title: "Multi-objective optimization of adhesive bonding process in constrained and noisy settings"
collection: publications
category: conferences
permalink: /publication/2023-ola-paper
excerpt: 'This study leverages Gaussian Process and Logistic Regression models within a Bayesian optimization framework to handle multi-objective, constrained, and uncertain adhesive bonding optimization, achieving efficient solutions with minimal experimental effort.'
date: 2023-05-27
venue: 'Communications in Computer and Information Science'
paperurl: 'https://doi.org/10.1007/978-3-031-34020-8_16'
slidesurl: '../files/OLA2023_adhesives.pdf'
citation: 'Morales-Hernández, A., Van Nieuwenhuyse, I., Rojas Gonzalez, S., Jordens, J., Witters, M., Van Doninck, B. (2023). &quot;Multi-objective Optimization of Adhesive Bonding Process in Constrained and Noisy Settings.&quot; In: Dorronsoro, B., Chicano, F., Danoy, G., Talbi, EG. (eds) Optimization and Learning. OLA 2023. <i>Communications in Computer and Information Science</i>. 1824. Springer, Cham.'
---

Finding the optimal process parameters for an adhesive bonding process is challenging: the optimization is inherently multi-objective (aiming to maximize break strength while minimizing cost), constrained (the process should not result in any visual damage to the materials, and stress tests should not result in adhesive failures), and uncertain (measuring the same process parameters several times lead to different break strength). Real-life physical experiments in the lab are expensive to perform (
6 h of experimentation and subsequent production costs); traditional evolutionary approaches are then ill-suited to solve the problem, due to the prohibitive amount of experiments required for evaluation. In this research, we successfully applied specific machine learning techniques (Gaussian Process Regression and Logistic Regression) to emulate the objective and constraint functions based on a limited amount of experimental data. The techniques are embedded in a Bayesian optimization algorithm, which succeeds in detecting Pareto-optimal process settings in a highly efficient way (i.e., requiring a limited number of experiments).
