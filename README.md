# ML-Quantum-Transport-in-Disordered-2D-Hexagonal-Materials

**📖 Abstract:**\
We introduce scalable machine learning models to accurately predict two key quantum transport properties, the transmission coefficient T(E) and the local density of states (LDOS) in two-dimensional (2D) hexagonal materials with magnetic disorder. Using a tight-binding Hamiltonian combined with the Non-Equilibrium Green’s Function (NEGF) formalism, we generate a large dataset of over 400,000 unique configurations across graphene, germanene, silicene, and stanene nanoribbons with varying geometries, impurity concentrations and en-
ergy levels. A central contribution of this work is the development of a geometry-driven, physically interpretable feature space that enables the models to generalize across material types and device sizes. Random Forest regression and classification models are evaluated in terms of accuracy, stability and extrapolation ability. Regression consistently outperforms classification in capturing of continuous transport behavior on in-domain data. However, extrapolation performance degrades significantly, revealing the limitations of tree-based models in unseen regimes. This study highlights both the potential and constraints of scalable ML models for quantum transport prediction and motivates future research into physics-informed or graph-based learning architectures for improved generalization in spintronic and nanoelectronic device design.


**📄 Conceptual Overview & Methodology**\
The machine learning workflow, feature space design, and physical interpretations are described in full detail in our accompanying paper. To understand the underlying algorithm, the rationale for the chosen geometric features, and the broader scientific context of this work, please refer to the manuscript:

"Scalable Machine Learning Models for Predicting Quantum Transport in Disordered 2D Hexagonal Materials"
Full text available on arXiv(arxiv.org/abs/2506.07983)

This repository provides the practical implementation to reproduce the results and figures from the paper.
