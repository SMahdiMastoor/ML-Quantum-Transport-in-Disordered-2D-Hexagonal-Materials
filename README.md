# ML-Quantum-Transport-in-Disordered-2D-Hexagonal-Materials

**📖 Abstract:**\
We introduce scalable machine learning models to predict two key electronic
properties of disordered two-dimensional hexagonal nanomaterials: the trans-
mission coefficient T(E) and the average local density of states (average-LDOS).
Using a tight-binding Hamiltonian combined with the Non-Equilibrium Green’s
Function formalism, the dataset of more than 400,000 unique nanoribbon con-
figurations across graphene, germanene, silicene, and stanene with varying ge-
ometries, impurity concentrations, and energy levels was generated. A central
contribution of this work is the development of a geometry-driven and phys-
ically interpretable feature space that enables generalization across material
classes and system sizes. Random Forest regression and classification models
are systematically evaluated in terms of accuracy, stability, and extrapolation
ability. Regression consistently outperforms classification in capturing contin-
uous transport behavior on in-domain data, while extrapolation performance
degrades, revealing the limitations of tree-based models in unseen regimes. This
study demonstrates a data-driven and transferable framework for accelerating
quantum transport prediction in 2D nanostructures with disorder, providing
new insights into structure–property relationships and guiding future develop-
ment of physics-informed learning models for materials science.


**📄 Conceptual Overview & Methodology**\
The machine learning workflow, feature space design, and physical interpretations are described in full detail in our accompanying paper. To understand the underlying algorithm, the rationale for the chosen geometric features, and the broader scientific context of this work, please refer to the manuscript:

"Scalable Machine Learning Models for Predicting Quantum Transport in Disordered 2D Hexagonal Materials"
Full text available on arXiv(arxiv.org/abs/2506.07983)

This repository provides the practical implementation to reproduce the results and figures from the paper.
