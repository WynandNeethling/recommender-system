
# Developing and Evaluating a Recommender System Using Matrix Factorisation and Alternating Least Squares

This repository contains a project on developing and evaluating a **Recommender System** based on **Matrix Factorisation** and the **Alternating Least Squares (ALS)** algorithm. The system was implemented from first principles, with a focus on understanding the fundamental concepts and mechanics behind recommendation algorithms.

## Overview

The project involves:
1. **Matrix Factorisation**:
   - Factorizing the user-item interaction matrix into latent feature matrices for users and items.
   - Using these matrices to predict missing entries in the interaction matrix.

2. **Alternating Least Squares (ALS)**:
   - Employing the ALS algorithm to iteratively optimize the latent matrices.
   - Implementing the method entirely from scratch for a detailed understanding.

3. **Performance Evaluation**:
   - Testing the recommender system on different datasets.
   - Evaluating using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

4. **Optimization**:
   - Using the **Numba** library to optimize critical computations for improved efficiency.

## Key Features

- **First-Principle Implementation**: The entire recommender system, including matrix factorisation and ALS, was implemented from scratch without relying on pre-built libraries.
- **Optimization with Numba**: Computationally intensive parts of the code were optimized using the Numba library to enable faster matrix operations and iterations.
- **Evaluation Metrics**: The system was evaluated on standard metrics to measure accuracy and performance.
- **Customizable Parameters**: Includes tunable hyperparameters such as the regularization term, learning rate, and the number of latent factors.

## Technologies Used

- **Numba**: Used for just-in-time compilation to enhance performance during matrix operations and ALS iterations.
- **Python**: The entire system was developed using Python with standard numerical libraries.

## Results

- **RMSE and MAE**: Detailed evaluation results for training and testing datasets.
- **Visualization**: Plots showing the performance of the system over iterations.
- **Optimization Impact**: A comparison of runtime with and without Numba optimizations.
