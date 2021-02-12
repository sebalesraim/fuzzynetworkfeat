# Fuzzy Network Features

This repository contains the codes for the computation of the fuzzy topological descriptors as described in 

_Measuring topological descriptors of complex networks under uncertainty_

Sebastian Raimondo and Manlio De Domenico

Physical Review E 103, 022311 – (2021)

## Introduction

Revealing the structural features of a complex system from the observed collective dynamics is a fundamental problem in network science. To compute the various topological descriptors commonly used to characterize the structure of a complex system (e.g., the degree, the clustering coefficient, etc.), it is usually necessary to completely reconstruct the network of relations between the subsystems. Several methods are available to detect the existence of interactions between the nodes of a network. By observing some physical quantities through time, the structural relationships are inferred using various discriminating statistics (e.g., correlations, mutual information, etc.). In this setting, the uncertainty about the existence of the edges is reflected in the uncertainty about the topological descriptors. In this study, we propose a methodological framework to evaluate this uncertainty, replacing the topological descriptors, even at the level of a single node, with appropriate probability distributions, eluding the reconstruction phase. Our theoretical framework agrees with the numerical experiments performed on a large set of synthetic and real-world networks. Our results provide a grounded framework for the analysis and the interpretation of widely used topological descriptors, such as degree centrality, clustering, and clusters, in scenarios in which the existence of network connectivity is statistically inferred or when the probabilities of existence $\pi_{ij}$ of the edges are known. To this purpose, we also provide a simple and mathematically grounded process to transform the discriminating statistics into the probabilities $\pi_{ij}$.

## Description
Three files are provided. Each file contains one network, corresponding to a specific Alaska community, namely

Kaktovi (37 layers, 164 nodes)
Venetie (43 layers, 206 nodes)
Wainwright (36 layers, 218 nodes)
in extended edgelist format:

nodeFrom layerFrom nodeTo layerTo weight
For further details about the calculation of weights, we refer to the aforementioned paper.

## Acknowledgments
The authors thank Alice Swartz and J.G. Young for their time and the valuable suggestions.

## Credits
Please cite the accompanying paper, if you use our codes in your study.
