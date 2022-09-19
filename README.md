# 2d-arm-model

This notebook implements the biomechanical primate arm model used in the following works:

- "Iterative Linear Quadratic Regulator Design for Nonlinear Biological Movement Systems."
W. Li and E. Todorov, International Conference on Informatics in Control (2004)

- "Preference Distributions of Primary Motor Cortex Neurons Reflect Control Solutions Optimized for Limb Biomechanics."
T. Lillicrap and S. Scott, Neuron (2013)

- "Population subspaces reflect movement intention for arm and brain-machine interface control."
H. Lalazar, J.M. Murray, L.F. Abbott, E. Vaadia, BioRxiv (2019)

The model in this notebook is an implementation based on the last reference above, with the additional inclusion of gravitational force and the option to have the arm move on an inclined plane rather than in the horizontal plane. This makes the model useful for studying the muscle control needed both for movement and for maintaining a fixed posture.
