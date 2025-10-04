---
title: "Multi-objective Hyperparameter Optimization with Performance Uncertainty."
collection: publications
category: conferences
permalink: /publication/2022-ola-paper
excerpt: 'This paper proposes a hybrid multi-objective hyperparameter optimization method that combines Tree-structured Parzen Estimators with Gaussian Process Regression under heterogeneous noise, improving performance under uncertainty compared to stand-alone approaches.'
date: 2022-12-11
venue: 'Communications in Computer and Information Science'
paperurl: 'https://doi.org/10.1007/978-3-031-22039-5_4'
slidesurl: '../files/OLA2022-hpo.pdf'
citation: 'Morales-Hernández, A., Van Nieuwenhuyse, I., Nápoles, G. (2022). &quot;Multi-objective Hyperparameter Optimization with Performance Uncertainty.&quot; In: Dorronsoro, B., Pavone, M., Nakib, A., Talbi, EG. (eds) Optimization and Learning. OLA 2022. <i>Communications in Computer and Information Science</i>. 1684. Springer, Cham.'
---

The performance of any Machine Learning algorithm is impacted by the choice of its hyperparameters. As training and evaluating a ML algorithm is usually expensive, the hyperparameter optimization (HPO) method needs to be computationally efficient to be useful in practice. Most of the existing approaches on multi-objective HPO use evolutionary strategies and metamodel-based optimization. However, few methods account for uncertainty in the performance measurements. This paper presents results on multi-objective HPO with uncertainty on the performance evaluations of the ML algorithms. We combine the sampling strategy of Tree-structured Parzen Estimators (TPE) with the metamodel obtained after training a Gaussian Process Regression (GPR) with heterogeneous noise. Experimental results on three analytical test functions and three ML problems show the improvement in the hypervolume obtained, when compared with HPO using stand-alone multi-objective TPE and GPR.
