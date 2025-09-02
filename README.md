# RSE-GDA
Official implementation of the **Riesz s-Energy based Gradient Descent Algorithm (RSE-GDA)** for
optimal μ-point distribution on linear, concave, and convex manifolds in 2D and 3D.  
This code accompanies the paper "Approximating Optimal \mu-point Distributions over
a Generalized Sphere for Riesz s-energy using a Gradient Descent Algorithm"

## Structure
- `2D/`: 2-dimensional manifolds  
- `3D/`: 3-dimensional manifolds  
- Each folder contains scripts for: `linear`, `concavity_2`, `concavity_5`, `convexity_0.5`, `convexity_0.25`.

## Features
- Generates initial points on manifolds  
- Computes Riesz s-energy and gradient  
- Projects gradients onto the tangent space  
- Runs gradient descent with Strong Wolfe line search  
- Saves optimized points, energy values, and plots  
