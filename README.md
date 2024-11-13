# Solving the 1D Wave Equation using Physics-Informed Neural Networks (PINN)

This project focuses on solving the 1D wave equation, a fundamental equation that describes the propagation of waves, such as sound, light, or water waves, and can be applied in various fields like acoustics, optics, and fluid dynamics. The goal is to model the wave's behavior over time and space using a Physics-Informed Neural Network (PINN), which integrates physical laws directly into the neural network's training process.

A PINN model is trained to satisfy the wave equation, as well as the initial and boundary conditions, using a deep neural network. The network's loss function includes terms for the wave equation, initial displacement, initial velocity, and boundary conditions, ensuring the model adheres to the physics of the problem. The network is trained using random training points in the spatial and time domains, with optimization techniques such as gradient clipping used to improve stability.

Once trained, the model's predictions are tested against the solution of the wave equation, and performance is evaluated using metrics like mean squared error and relative error. The project demonstrates the ability of PINNs to solve partial differential equations with physical constraints.
