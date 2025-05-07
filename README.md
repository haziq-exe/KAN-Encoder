# KAN-Encoder

This repository explores a U-Net-style image encoder-decoder architecture using Kolmogorov-Arnold Networks (KANs) in place of standard convolutional layers. The goal is to evaluate whether KAN-based convolutional layers offer performance improvements over traditional methods in image reconstruction tasks.

## Summary

- Implements a U-Net architecture using convolutional KAN layers.
- Utilizes [Convolutional-KANs](https://github.com/AntonioTepsich/Convolutional-KANs) as the core building blocks.

## Findings

- KAN-based models are significantly slower to train and infer.
- No observed improvement in reconstruction performance over conventional U-Net models.
- Further quantitative analysis and benchmarking of KAN performance against standard CNNs in terms of number of nodes and model efficiency pending


- Dependencies from [Convolutional-KANs](https://github.com/AntonioTepsich/Convolutional-KANs)
