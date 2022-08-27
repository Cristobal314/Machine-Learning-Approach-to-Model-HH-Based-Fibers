# Machine-Learning-Approach-to-Model-HH-Based-Fibers
Hodgkin &amp; Huxley model reduction based on Autoencoder
The code associated with the Machine Learning Approach to model Hodgkin & Huxley Based Fibers project is stored in this repository. This project aims 

1. Carry out simulations in NEURON of models of a single neuron for a fixed input stimulus and with variations in the model parameters.  
2. Approach unicompartmental and bicompartmental modeling and simulation with NEURON.  
3. Through the data generated, reduce the number of state variables of the dynamic system with a deterministic Autoencoder and thereby obtain a two-dimensional representation of the oscillatory, excitable and non-excitable states of the system.  
4. Reduce the number of parameters of the two-compartment model through an Autoencoder.  

The present hypothesis is that an explanation of the oscillatory phenomena of the dynamics in the system can be reduced to a two-dimensional system, given that for the unicompartmental case there are models such as FitzHugh - Nagumo with two state variables and in [1] a model that reduces the parameters to two dimensions, one associated with the structure of the neuron and another associated with the dynamics of the gate variables.

[1] Ori, H., Marder, E. & Marom, S. (2018) Cellular function given parametric variation in the Hodgkin and Huxley model of excitability. Proceedings of the National Academy of Sciences, 115 (25), E8211 - E8218. https://doi.org/10.1073/pnas.1808552115
