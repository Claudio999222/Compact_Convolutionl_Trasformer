# Compact_Convolutional_Transformer (CCT) Object Recognition

## Overview

This notebook showcases the training of a Compact Convolutional Transformer (CCT) on the CIFAR-100 dataset for object recognition. The CCT architecture is employed for its efficiency and achieves impressive results, considering the challenges presented by the dataset.

## Performance Metrics

The trained CCT model has demonstrated excellent performance, achieving:

- **Top-5 Accuracy:** 80%
- **Accuracy:** 50%

## Known Issue

There was an issue with saving the model weights. The callback used to save the weights loaded the weights from the previous training session and did not save the best weights. Despite this, the training logs from TensorBoard are available for a more detailed analysis.
