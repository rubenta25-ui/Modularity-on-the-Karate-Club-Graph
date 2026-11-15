# Modularity-on-the-Karate-Club-Graph
Objective:
This notebook applies spectral modularity maximisation to the Zachary Karate Club graph. The aim is to identify groups of vertices (communities) whose members are more densely connected to one another than would be expected under a degree-preserving random-network model.

The workflow is:

Construct and inspect the original network.
Build its modularity matrix.
Use an eigenvector of that matrix to obtain an initial bipartition.
Recursively split communities when the relevant leading eigenvalue is positive.
Examine how standard network measures behave on the original graph and on graphs retaining only within-community edges.
The notebook uses NetworkX for graph operations, NumPy for matrix and eigenvalue calculations, and Matplotlib for visualisation.

# A Note on Responsible AI Usage
I used ChatGPT as a supporting tool while working on this assignment. It helped me with visualisations, implementing the algorithms, reviewing my notebook for errors, and refining the explanatory text. However, it was not a substitute for my own understanding of the concepts. I ran the notebook myself, checked the outputs for consistency, and take full responsibility for the code, analysis, and conclusions presented in this submission.
