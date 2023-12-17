# Contlo-AI-Assignment
Coding Assignment: Implementation and Optimization of GPT-2 Model
This repository contains a PyTorch implementation of the GPT model, a powerful language model based on the Transformer architecture.

## Usage

To integrate the GPT model into your project, follow these steps:

1. Import the necessary libraries:

    ```python
    import torch
    from torch import nn
    import torch.nn.functional as F
    import math
    ```

2. Configuration class for GPT model hyperparameters


3. Main GPT model class


4. Transformer block class
   

5. Multihead Attention class


6. Example usage with 125 million parameters

## Model Architecture

The GPT model consists of token embedding, positional encoding, attention blocks, layer normalization, and a final linear layer. Each block contains a multihead attention mechanism and a feedforward neural network.

## Training Configuration

The model is initialized using Xavier uniform weights for linear and embedding layers. Layer normalization is applied, and dropout is used for regularization.

## Reference Materials

1. "Attention Is All You Need" paper by Vaswani et al. (2017): https://arxiv.org/abs/1706.03762
2. PyTorch documentation: https://pytorch.org/


