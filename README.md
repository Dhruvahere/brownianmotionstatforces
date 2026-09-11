Brownian Dynamics is a type of simulation based on the equation discovered by Albert Einstein and is often used for Molecular Dynamics simulations all over, with custom force fields and using special calculus in order to update the molecule's position as a function of a set of it's evolving parameters (like temperature, molecular distance, etc.)

Diffusion Generative Models learn a score function that is a log density function. This log density function is also the same as the negative gradient of a potential, which constitutes the forces that make up a simulation of some molecule. 

So naturally the question is, if I use the log density function of a diffusion model in Brownian dynamics, how different are my outputs and can we predict shapes? 
