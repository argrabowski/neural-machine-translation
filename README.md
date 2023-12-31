# Neural Machine Translation

This repository contains an implementation of a neural machine translation (NMT) model for translating English to French. The model is built using PyTorch and incorporates a scaled dot-product attention mechanism.

## Overview

1. **Scaled Dot-Product Attention Mechanism:** Implements functions for scaled dot-product attention and multi-head scaled attention. This attention mechanism is commonly used in transformer models.

2. **Neural Machine Translation Model:** Defines a sequence-to-sequence model for English to French translation. It includes data preprocessing, the definition of encoder and decoder models using GRU layers, training the model, and evaluating its performance. GloVe word embeddings are utilized for initializing the encoder's embedding layer.

## Dependencies

- Python (>=3.6)
- PyTorch
- NumPy
- Matplotlib
- TorchText
- Scikit-learn

## Usage

1. Clone the repository:

```bash
git clone https://github.com/argrabowski/neural-translation.git
cd neural-translation
```

2. Run the Jupyter notebook `neural-translation.ipynb` to explore the code, train the model, and visualize results.

3. Adjust hyperparameters, experiment with different configurations, and explore the code to understand the implementation details.
