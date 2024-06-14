# Emerging NeoHebbian Dynamics in Forward-Forward Learning: Implications for Neuromorphic Computing

## Authors
- **Erik B. Terres-Escudero** (DeustoTech, University of Deusto) [ORCID](https://orcid.org/0009-0003-9781-7657)
- **Javier Del Ser** (TECNALIA, Basque Research & Technology Alliance (BRTA); University of the Basque Country (UPV/EHU)) [ORCID](https://orcid.org/0000-0002-1260-9775)
- **Pablo García-Bringas** (DeustoTech, University of Deusto) [ORCID](https://orcid.org/0000-0003-3594-9534)

## Overview

This repository contains the implementation of the work from the paper "Emerging NeoHebbian Dynamics in Forward-Forward Learning: Implications for Neuromorphic Computing". Our study explores the integration of Hebbian learning dynamics with the Forward-Forward Algorithm (FFA), offering insights into biologically plausible learning mechanisms and their potential applications in neuromorphic computing.

## Abstract

Advances in neural computation have predominantly relied on the gradient backpropagation algorithm (BP). However, the recent shift towards non-stationary data modeling has highlighted the limitations of this heuristic, exposing that its adaptation capabilities are far from those seen in biological brains. Unlike BP, where weight updates are computed through a reverse error propagation path, Hebbian learning dynamics provide synaptic updates using only information within the layer itself. This has spurred interest in biologically plausible learning algorithms, hypothesized to overcome BP's shortcomings. In this context, Hinton recently introduced the Forward-Forward Algorithm (FFA), which employs local learning rules for each layer and has empirically proven its efficacy in multiple data modeling tasks. In this work we argue that when employing a squared Euclidean norm as a goodness function driving the local learning, the resulting FFA is equivalent to a neo-Hebbian Learning Rule. To verify this result, we compare the training behavior of FFA in analog networks with its Hebbian adaptation in spiking neural networks. Our experiments demonstrate that both versions of FFA produce similar accuracy and latent distributions. The findings herein reported provide empirical evidence linking biological learning rules with currently used training algorithms, thus paving the way towards extrapolating the positive outcomes from FFA to Hebbian learning rules. Simultaneously, our results imply that analog networks trained under FFA could be directly applied to neuromorphic computing, leading to reduced energy usage and increased computational speed.

## Code and Data

### Code

The entire code is contained within the notebook "training.ipynb". This notebook includes implementations related to two research questions: training (Research Question 1) and behavioral analysis (Research Question 2). It features has teh implementation for both Hebbian and analog versions of the Forward-Forward Algorithm.

### Data

The data is located in the "results" folder, which contains two subfolders:

- **latents/\***: This folder contains the latent vectors of the data from the test datasets for easy access.
- **models/\***: This folder stores the trained checkpoints of the models obtained during the experiments.


## Contact
For questions or collaboration inquiries, please contact:
- **Erik B. Terres-Escudero**: [e.terres@deusto.es](mailto:e.terres@deusto.es)
