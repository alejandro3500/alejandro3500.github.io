---
title: "Strategic NPI Optimisation: Solving a MOOP to Mitigate Healthcare Burden and Educational Loss"
collection: talks
type: "Poster"
permalink: /talks/2026-DT4PH-poster
venue: "Digital Twins and AI in Personalized Healthcare (DT4PH): from Innovation to Implementation and Impact"
date: 2026-06-10
location: "Leuven, Belgium"
---

Digital twins and AI-driven decision-support tools are promising for public health, enabling policymakers to evaluate intervention strategies before implementation and thereby reducing societal harm. Yet, operational frameworks that couple realistic and age-structured transmission models with the explicit quantification of trade-offs among competing objectives remain scarce. We present a simulation-based digital twin framework for population-level pandemic decision support, illustrated through a concrete case study in Belgium: optimizing contact-reduction schedules to balance healthcare-system pressure against disruption to in-person education during COVID-19. The framework evaluates candidate contact-reduction schedules using hospitalization burden, derived from simulated ICU and non-ICU bed occupancy relative to capacity, and educational loss, represented as a contact-based proxy for reduced in-person learning opportunities. These two interpretable objectives were selected for their policy relevance and connection to real-world data.

Decision variables encode proportional changes in eight school and workplace contact components over eight two-week intervals, defining a 64-dimensional decision space. The resulting contact structures are propagated through a Digital Twin implemented as an age-structured stochastic SARS-CoV-2 transmission model to evaluate both objectives. The study period, November 2020 to February 2021, corresponds to hospitalization pressure and moderate-to-high intervention stringency in Belgium. To explore this high-dimensional space, we used AI-assisted optimization algorithms, including NSGA-II and Bayesian optimization with Tree-structured Parzen estimators and Gaussian Process regression.

Results indicate that the Pareto front includes strategies that improved the contact structure observed during the same pandemic period. Analysis of the associated contact-reduction schedules suggests that, during the high-stringency phase from mid-November 2020 to early January 2021, Pareto-optimal strategies tend to preserve relatively more school contacts while favoring stronger reductions in workplace contacts, particularly for high-proximity occupations. Although operational deployment requires further validation, the framework demonstrates how digital twins, AI-assisted optimization, and interpretable contact-scaling schedules can support responsible public health decision-making by suggesting potential trade-off strategies before implementation.


[View Poster](..\files\Poster_dt4ph_2026.pdf)
