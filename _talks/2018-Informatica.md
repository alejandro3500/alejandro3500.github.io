---
title: "Majority vote modification to consider the classifier experience on multi-classifier systems"
collection: talks
type: "Talk"
permalink: /talks/2018-Informatica
venue: "INTERNATIONAL CONFERENCE ON INFORMATICS AND COMPUTER SCIENCE (CICCI 2018)"
date: 2018-03-20
location: "La Havana, Cuba"
---

Classification techniques are widely used to solve problems that require categorizing objects according to their characteristics. Numerous classification models have been reported in the literature, including neural networks, Bayesian algorithms, and decision trees. However, in certain domains, such as bioinformatics, it is often more intuitive and effective to combine the outputs of multiple classifiers.

Among the most popular classifier combination methods are Bagging and Boosting, which rely on a single model type, and Stacking, which introduces a meta-learner trained on the outputs of base classifiers. Another common approach is voting-based classification, where classifiers vote for the class they consider correct.

The majority voting rule implemented in WEKA only considers the predictions of base classifiers for each individual instance, without accounting for their prior performance. This work proposes a modified majority voting method in which voting is dynamically adjusted according to the experience gained during the system’s classification process.

The proposed approach was validated using 12 datasets and 6 individual classifiers, and its performance was compared with well-known models from the literature. Statistical tests showed that the proposed modification significantly outperformed the original majority voting method and, in some cases, even achieved better results than Stacking.


[View text](..\files\Informatica 2018 v3 Final.pdf)
