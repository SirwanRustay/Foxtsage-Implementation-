# Foxtsage-Implementation-
This repository showcases the implementation of the Foxtsage algorithm. It includes the code and detailed insights into how the Foxtsage optimizer works, along with a comparison of its performance against the Adam optimizer.
Here's a detailed README template for your GitHub repository:

---

# Foxtsage Optimizer Implementation

This repository contains the implementation of the **Foxtsage** optimization algorithm, which is a nature-inspired optimization technique designed for machine learning tasks. The repository includes the code for training and testing the optimizer, along with comparisons of its performance against the widely-used **Adam optimizer** on various datasets.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Optimizer Details](#optimizer-details)
- [Results](#results)
- [License](#license)

## Overview

The **Foxtsage** algorithm is a novel optimization technique inspired by nature. It is designed to efficiently solve complex optimization problems, particularly in the context of training deep neural networks. This repository provides a Kaggle notebook demonstrating how to implement the Foxtsage optimizer, train a Convolutional Neural Network (CNN) on the MNIST dataset, and evaluate its performance in comparison to the **Adam optimizer**.

## Installation

To use the code and run experiments locally, clone this repository and install the required dependencies.

1. Clone the repository:
   ```bash
   git clone https://github.com/SirwanRustay/Foxtsage-Implementation-.git
   cd foxtsage-optimizer
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the Foxtsage optimizer with a deep neural network:

1. Open the `foxtsage_optimizer_notebook.ipynb` notebook in Jupyter or Kaggle.
2. The notebook will guide you through the steps to:
   - Load the dataset (e.g., MNIST).
   - Train a CNN model using the **Foxtsage** optimizer.
   - Evaluate and compare performance metrics (accuracy, precision, recall, F1-score) with the **Adam optimizer**.

## Optimizer Details

### Foxtsage Optimizer

The Foxtsage optimizer is designed to address challenges in machine learning optimization problems. It combines the strengths of multiple nature-inspired algorithms to efficiently navigate the solution space and achieve faster convergence. The optimizer works by dynamically adjusting its learning rate based on a population of candidate solutions, improving the robustness and performance of deep learning models.

### Adam Optimizer

**Adam** (Adaptive Moment Estimation) is an adaptive learning rate optimization algorithm that combines the advantages of both the **AdaGrad** and **RMSProp** optimizers. It computes adaptive learning rates for each parameter by considering both the first and second moments of the gradients.

## Results

The notebook includes results comparing the performance of **Foxtsage** against **Adam** on the MNIST dataset. The metrics considered include:

- **Training Loss**
- **Validation Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Performance graphs and tables are provided for clear visualization and analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Cite as :

Sirwan A. Aula, Tarik A. Rashid. (2024). Foxtsage vs. Adam: Revolution or Evolution in Optimization?.Arxiv 
https://doi.org/10.48550/arXiv.2412.17855

Sirwan A. Aula, Tarik A. Rashid.(2025). FOX-TSA: Navigating Complex Search Spaces and Superior Performance in Benchmark and Real-World Optimization Problems, Ain Shams Engineering Journal, Vol 16, Issue 1,https://doi.org/10.1016/j.asej.2024.103185

Sirwan A. Aula, Tarik A. Rashid. (2024). FOX-TSA hybrid algorithm: Advancing for superior predictive accuracy in tourism-driven multi-layer perceptron models, Systems and Soft Computing, Volume 6, https://doi.org/10.1016/j.sasc.2024.200178 
