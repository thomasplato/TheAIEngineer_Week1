# Capstone: Gradient-Based Optimization Case Study (Week 1)

This notebook explores several variants of **gradient-based optimization algorithms**, including:
- Standard Gradient Descent (GD).
- Heavy-Ball Momentum method
- Stochastic Gradient Descent (SGD)
- Gradient Descent with Decaying Learning Rate

The goal is to illustrate how different parameter choices (learning rate `η`, momentum `β`, and noise `σ`) affect convergence behavior and stability when approaching a minimum.

## Contents

1. **Gradient Descent and Heavy-Ball Augmentation**  
   Comparison of basic gradient descent with heavy-ball momentum. Visual analysis of convergence speed and oscillation effects.

2. **Stochastic Gradient Descent (SGD)**  
   Demonstrates the effect of noise (`σ`) on convergence and stability for a fixed learning rate.

3. **Gradient Descent with Decaying Learning Rate**  
   Shows how dynamically reducing the learning rate over iterations improves stability.

4. **Visualization and Convergence Analysis**  
   Plots illustrating the optimization paths and convergence of `f(x_k)` toward `f(x*)`.

After each plot and metrics calculation I comment in the Jupyter Notebook.

## Data

No external dataset is used. I use the function `f(x)` defined in the note 'Gradient-Based Optimization Case Study'. The function is a piecewise function with a kink at `x=3`. The function is defined as: f(x) = |½x³ - ½x²| + ½x
