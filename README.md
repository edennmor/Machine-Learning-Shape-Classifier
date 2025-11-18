# Machine Learning Shape Classifier – Python

## Overview
This project implements a Machine Learning–based image classifier designed to recognize and categorize geometric shapes using feedforward neural networks. The system generates its own synthetic dataset of shapes, trains the network using backpropagation, evaluates prediction accuracy, and visualizes classification results. The project demonstrates neural network architecture design, matrix-based computation, gradient-based learning, and performance analysis.

## Key Features
- Feedforward neural network with adjustable hidden layers
- Synthetic dataset generation for circles, ellipses, and triangles
- Training using gradient descent and backpropagation
- Accuracy evaluation and loss tracking
- Data preprocessing and normalization
- Visualization of predictions and training metrics

## Project Structure
| File | Description |
|--------|-------------|
| `NN-One.py` | Initial implementation of a feedforward neural network with training loop and backpropagation |
| `NN-Two.py` | Extended model with improved architecture and performance evaluation |
| `Our_Data.py` | Synthetic dataset generator producing geometric shape images |
| `Neural Networks.pdf` | Full project documentation, architecture explanation, and theoretical analysis |

## Technologies & Skills Demonstrated
- Python 3
- Neural networks & backpropagation
- Machine learning workflow (data → training → evaluation)
- Matrix operations & vectorized computation
- Synthetic dataset creation
- Performance measurement and tuning

## How It Works
1. The system generates a dataset of geometric shapes (circle, ellipse, triangle)
2. Input images are converted to vector representation
3. A neural network processes each sample through multiple layers
4. Backpropagation updates weights to minimize error
5. The model evaluates classification accuracy and outputs predictions

## Example Usage
```bash
python NN-Two.py
