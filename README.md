# Multimodal Channel-wise Image-guided Joint Diffusion

## Introduction

This repository contains the implementation of the paper "Cognitively Inspired Cross-Modal Data Generation
Using Diffusion Models". The paper presents a novel approach to generative AI that mimics human-like multimodal learning. The model is based on score-based diffusion models and is designed to be robust against noisy language inputs, generate correlated modalities in all directions, and provide a learning scheme that is empirically similar to biological neural networks.

## Abstract

The paper addresses the gap between human-like multimodal learning and AI by exploring a channel-wise image-guided multimodal joint diffusion training scheme. This scheme transforms and aligns multimodal data in the input space rather than in the learned latent space. The model trains on noisy data in all modalities, allowing for noisy language inputs as conditions in the process of conditional generation, enhancing robustness in diverse scenarios.

## Method

The method is based on score-based diffusion models. With joint training of all modalities, it enables channel-guided sampling from any modality to any modality.

## Results

The model was tested for unconditional joint sampling of all 4 channels without any guidance. It was observed that the approach is able to generate visually correlated classes from both CIFAR-10 and MNIST concurrently. The model also demonstrated the capability of relating MNIST class “0” to the CIFAR-10 class “airplane”. The results suggest that the channel-wise image guidance also helps in learning more meaningful latent space that encodes some shared features among these classes.

## Contributions

1. By transforming all input modalities into channel-concatenated spatial inputs, we enable multi-directional generation across all modalities using a single generative neural network.
2. Our model trains on noisy data in all modalities, allowing for noisy language inputs as conditions in the process of conditional generation, enhancing robustness in diverse scenarios.
3. Our model provides a learning scheme that is empirically similar to biological neural networks, aiming to inspire further research in this intriguing intersection of fields.

## Getting Started

### Prerequisites

```
# Please add the prerequisites or dependencies here
```

### Installation

```
# Please add the installation instructions here
```

### Running Experiments

```
# Please add the instructions to run the experiments here
```
