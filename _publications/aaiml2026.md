---
title: "Transfer Learning across Optimization Problems via the Constraint Composite Graph"
collection: publications
category: conferences
permalink: /publication/aaiml2026
excerpt: ''
date: 2026-03-22
venue: 'Proceedings of the 2026 International Conference on Advances in Artificial Intelligence and Machine Learning (AAIML-2026)'
paperurl: 'http://kellyzhengusc.github.io/files/aaiml26.pdf'
---


Optimization problems can often be formulated as Weighted Constraint Satisfaction Problems (WCSPs). However, despite the significance of WCSPs, very few Machine Learning (ML) algorithms have been developed for addressing predictive tasks on them. In this paper, we present a novel approach for efficiently and effectively addressing predictive tasks on WCSPs. Our approach is based on two cornerstone ideas: The first relates to the Constraint Composite Graph (CCG) and the second relates to FastMapSVR. The CCG is a graphical representation of a given WCSP instance that facilitates its reduction to an instance of the Minimum Weighted Vertex Cover (MWVC) problem by introducing some intelligently chosen auxiliary variables. FastMapSVR is a newly developed framework that facilitates regression tasks on complex objects. It works by comparing pairs of objects via a distance function instead of characterizing individual objects. While the MWVC problem serves as a common substrate for WCSPs, FastMapSVR is very effective on the MWVC problem when used with a maxflow-based distance function. Hence, our approach is effective on transfer learning tasks across various optimization problems formulated as WCSPs. We empirically demonstrate the success of our approach on instances of five optimization problems: the image segmentation, Combinatorial Auction (CA), random WCSP, Maximum Satisfiability (MaxSAT), and the Maximum a Posteriori (MAP) estimation problems.
