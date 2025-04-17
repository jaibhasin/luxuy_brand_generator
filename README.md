# Luxury Brand Name Generator

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/jaibhasin/luxuy_brand_generator)

A machine learning model that generates unique and creative luxury brand names using character-level language modeling.

## Overview

This project uses a neural network to learn patterns from existing luxury brand names and generate new, unique brand names. The model is built using PyTorch and implements character-level language modeling with the following features:

- Character-level embeddings
- Batch normalization
- Tanh activation
- Cross-entropy loss
- Mini-batch training

## Features

- Generates unique luxury brand names
- Learns from a curated dataset of luxury brands
- Implements advanced neural network architecture
- Includes training visualization tools
- Provides model evaluation metrics

## Requirements

- Python 3.12.4
- PyTorch
- Matplotlib
- Jupyter Notebook

## Installation

1. Clone the repository:
```bash
git clone https://github.com/jaibhasin/luxuy_brand_generator.git
cd luxuy_brand_generator
```

2. Install the required packages:
```bash
pip install torch matplotlib jupyter
```

## Dataset

The project uses a curated dataset of luxury brand names stored in `brands_list.txt`. The dataset includes brands from various luxury sectors including fashion, watches, jewelry, and automotive. The data was sourced from:

- [Brandirectory Luxury and Premium Report](https://brandirectory.com/reports/luxury-and-premium)
- [TopsLuxury Store Designers](https://topsluxury.store/designers)
- Additional brand names curated with the assistance of Claude AI

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook luxury_brand_name.ipynb
```

2. Run the cells in sequence to:
   - Load and preprocess the data
   - Initialize the model
   - Train the model
   - Generate new brand names

3. To generate new brand names, use the provided generation function with different random seeds for variety.

## Model Architecture

The model consists of:
- Character embeddings (4 dimensions)
- Hidden layer (100 neurons)
- Batch normalization
- Tanh activation
- Output layer for character prediction

## Training

The model is trained using:
- Mini-batch gradient descent
- Learning rate scheduling
- Cross-entropy loss
- Batch normalization

## Evaluation

The model's performance can be evaluated using:
- Training loss
- Validation loss
- Test loss
- Generated name quality

## Results

The model achieves:
- Training loss: ~2.55
- Validation loss: ~3.16
- Generates creative and unique brand names

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Dataset sources:
  - [Brandirectory](https://brandirectory.com/reports/luxury-and-premium) for luxury brand rankings and data
  - [TopsLuxury Store](https://topsluxury.store/designers) for comprehensive designer listings
  - Claude AI for assistance in data curation and validation
- Inspired by character-level language modeling techniques
- Special thanks to the open-source community for PyTorch and related tools 