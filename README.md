# RBF Networks, Competitive Learning, & SOMs

## Project Overview
This project investigates **Radial Basis Function (RBF) Networks**, **Competitive Learning**, and **Self-Organizing Maps (SOMs)** for function approximation, clustering, and self-adaptive learning.

## Technologies & Tools Used
- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib
- **Network Types**: Radial Basis Function (RBF) Networks, Competitive Learning, Self-Organizing Maps (SOM)
- **Optimization Methods**: Least Squares, Delta Rule, Competitive Learning, Gaussian Neighborhood Functions

## Key Features

### RBF Networks & Function Approximation
- **Batch vs. Online Learning**: Batch learning achieves **lower residual errors**.
- **Impact of RBF Width (σ)**: Optimized width **balances bias-variance tradeoff**.
- **Least Squares vs. Delta Rule**: Least Squares provided **smoother approximations**, while Delta Rule had **higher variability**.

### Competitive Learning
- **Node Positioning & Initialization**: Evaluated **random vs. structured initialization**.
- **Multi-Winner CL**: Improved weight updates, preventing dead neurons.
- **Application to Function Approximation**: Used **ballistic trajectory modeling** to test learning effectiveness.

### Self-Organizing Maps (SOMs)
- **Topological Ordering**: Successfully clustered **animal species** based on features.
- **Cyclic Tour Problem**: Used **SOMs for route optimization**, but struggled with exact solutions.
- **Clustering Political Data**: Analyzed Swedish political party distributions in **two-dimensional maps**.

## Results
- **RBF Networks** successfully approximate smooth functions but struggle with discontinuous ones.  
- **Competitive Learning** improves network initialization but requires careful tuning.  
- **SOMs effectively cluster data** but are **sensitive to initialization** and **do not guarantee optimal solutions**.  
- **Multi-winner CL improves RBF unit distribution**, preventing dead neurons and enhancing function approximation.  
