# Vision Transformer (ViT) from Scratch (PyTorch)

This repository contains a step-by-step guide and implementation of a Vision Transformer (ViT) from scratch using PyTorch. The implementation is focused on understanding the core concepts of ViT architecture by building it step by step.

## Introduction

Vision Transformers (ViT) have emerged as powerful architectures in the field of Computer Vision since their introduction by Dosovitskiy et al. in 2020. ViT has shown state-of-the-art performance in various computer vision tasks, including image classification, by leveraging the transformer model.

## Implementation Details

The implementation provided in this repository covers the following key components of the ViT architecture:

1. **Patchify and Linear Mapping**: Breaking down input images into patches and mapping each patch to a vector using a linear layer.
2. **Adding Classification Token**: Introduction of a special classification token to capture global information about the image.
3. **Positional Encoding**: Incorporating positional encoding to provide spatial information to the model.
4. **Multi-head Self Attention (MSA)**: Implementation of the MSA block to enable the model to capture relationships between different
