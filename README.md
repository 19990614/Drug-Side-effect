# Multimodal Input-Based Graph Neural Networks for High-Throughput Prediction of Drug-Induced Anemia Side Effects

This repository contains the official implementation of the article **"Multimodal Input-Based Graph Neural Networks for High-Throughput Prediction of Drug-Induced Anemia Side Effects"**. The project is designed to predict drug-induced anemia side effects using Graph Neural Networks (GNNs) and multimodal input data.

## Overview

Drug-induced anemia is a significant concern in drug development. This project utilizes advanced GNN architectures to improve the accuracy of anemia side effect predictions. The model incorporates multimodal data, including molecular graphs and numerical descriptors, for high-throughput prediction.

## Repository Structure

- `model_building.py`: Defines the GCN (Graph Convolutional Network) architecture.
- `model_training.py`: Implements the training logic for the GCN model.
- `model_testing.py`: Includes the evaluation logic for testing the trained model.
- `main.py`: Orchestrates the workflow, including data loading, model training, and testing.
- `data/`: Directory to store input datasets and processed data files.
- `saved_models/`: Directory to store trained model weights.

## Requirements

The project requires the following libraries:
- Python 3.8-3.9
- PyTorch
- DGL
- scikit-learn
- NumPy

To install the dependencies, run:
```bash
pip install -r requirements.txt
