---
title: "FastMapSVM/FastMapSVR for Predictive Tasks on CSPs, SAT, and Weighted CSPs"
collection: publications
category: conferences
permalink: /publication/icmla2024
date: 2024-01-01
venue: 'Proceedings of the Twenty-Third International Conference on Machine Learning and Applications (ICMLA-2024)'
paperurl: 'http://kellyzhengusc.github.io/files/icmla24.pdf'
---


Predictive tasks on Constraint Satisfaction Problems (CSPs), Satisfiability (SAT) problems, and Weighted CSPs (WCSPs) are usually NP-hard but can also be modeled as classification or regression problems suitable for Machine Learning (ML) algorithms. While most existing ML algorithms have had only limited success on such tasks, a newly developed ML framework, called FastMapSVM, has been shown to be successful for predicting CSP satisfiability. FastMapSVM leverages a distance function between pairs of CSP instances instead of trying to characterize individual CSP instances. In this paper, we advance FastMapSVM in various ways. For predicting the satisfiability of CSP and SAT instances, we design a distance function that utilizes maxflow computations and strong path-consistency (or a truncated version of it). For predicting the optimal cost of WCSP instances, we design a distance function that also utilizes maxflow computations and replaces the Support Vector Machine (SVM) component of FastMapSVM by a Support Vector-based Regression (SVR) component. We demonstrate the success of our FastMapSVM/FastMapSVR approach over competing state-of-the-art ML algorithms in all three domains: In the CSP domain, we demonstrate our success on several CSP benchmark suites; in the SAT domain, we demonstrate our success on hard 3-SAT instances drawn from the phase transition region; and in the WCSP domain, we demonstrate our success on a wide range of randomly generated WCSP instances.
