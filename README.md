# MNIST Classification with Confusion Analysis

A compact deep learning project that trains a CNN on MNIST digits, analyzes classification confusions, and visualizes embeddings.

## Features

- **CNN Model**: Custom architecture for digit classification
- **Confusion Matrix**: Identifies most confused digit pairs  
- **UMAP Visualization**: 2D embedding visualization of confused classes
- **Triplet Loss Ready**: Framework prepared for metric learning

## Quick Start

```bash
pip install torch torchvision pytorch-metric-learning umap-learn
jupyter notebook confusion_triplet_mohammad_mofidi.ipynb
