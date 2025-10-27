# Physics-Informed Neural Networks (PINNs)

This repository contains introductory and applied implementations of **Physics-Informed Neural Networks (PINNs)**.  
The purpose of this work is to understand how neural networks can be used to solve differential equations by embedding physical laws into the learning process.  
These implementations are created **purely for learning and experimentation**.

---

## Project Overview

PINNs are a class of neural networks that combine data-driven learning with known physical equations, such as PDEs or ODEs.  
They minimize both data loss and physics-based residual loss, allowing the model to satisfy governing equations while fitting observed data.

This repository includes two main implementations:

1. **`PINN.ipynb`**  
   - Basic implementation of a PINN for conceptual understanding.  
   - Trained on a **dummy dataset** to demonstrate how physics constraints are incorporated into loss functions.  
   - Covers network architecture, physics-based loss, and training visualization.

2. **`PINN_on_Burger_equation.ipynb`**  
   - Full PINN model trained on the **[PDE Dataset (Burgers’ Equation)](https://www.kaggle.com/datasets/scaomath/pde-dataset?select=burgers_v1000_smooth_1024.mat)**.  
   - Demonstrates solving partial differential equations using physics-based supervision.  
   - Implements data preprocessing, network setup, and loss minimization using both data and PDE residuals.  
   - Focused on practical understanding of training PINNs on real physical systems.

---

## Key Concepts

- Combines **data loss** and **PDE residual loss** in the training objective.  
- Enforces **physical constraints** directly in the learning process.  
- Enables solving differential equations without relying solely on labeled data.  
- Demonstrates the relationship between **neural network outputs** and **governing physics laws**.

---

## Things Learned

- Understood how **neural networks can approximate PDE solutions** through residual minimization.  
- Learned the structure and loss design of a **Physics-Informed Neural Network**.  
- Explored training stability and error behavior in PINNs.  
- Gained experience implementing **physics-based models** in PyTorch.  
- Developed intuition for extending PINNs to more complex physics-driven problems.

---
