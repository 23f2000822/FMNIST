# FMNIST Model Optimization Results

This repository contains different versions of a Fashion MNIST (FMNIST) model optimized using various techniques. Below is a summary of each model's accuracy and size after applying the corresponding optimization method.

| Model                     | Accuracy | Size   |
|---------------------------|----------|--------|
| Baseline model (no optimization) | 0.91     | 706 KB |
| Post-training quantization | 0.91     | 184 KB |
| Quantization aware training | 0.92     | 183 KB |
| Weight pruning             | 0.90     | 240 KB |
| Weight clustering          | 0.91     | 125 KB |
| Collaborative Optimization | 0.90     | 56 KB  |

## Overview of Optimization Techniques

- **Baseline model:** The original trained model without any size or performance optimization.
- **Post-training quantization:** Reduces model size by quantizing weights after training.
- **Quantization aware training:** Incorporates quantization during training for improved accuracy.
- **Weight pruning:** Removes less important weights to reduce model complexity.
- **Weight clustering:** Groups similar weights to reduce storage requirements.
- **Collaborative Optimization:** Combines pruning, clustering, and quantization for maximum size reduction.

## Usage

The optimized models are saved in this repository and can be used for deployment on resource-constrained devices such as microcontrollers and SBCs.


