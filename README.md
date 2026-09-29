# Pneumonia Detection Using CNN

An image-classification project that explores convolutional neural networks for classifying chest X-ray images.

## Problem

Chest X-rays are commonly used when evaluating pneumonia. This project focuses on learning visual patterns from labeled images and classifying them into predefined categories.

## Pipeline

1. Organize images by class.
2. Resize and normalize images.
3. Split data into training, validation, and test sets.
4. Optionally apply augmentation such as rotation, flipping, and zooming.
5. Train a convolutional neural network.
6. Evaluate the model on unseen data.

## Example CNN Structure

```text
Input
→ Convolution + ReLU
→ Max Pooling
→ Convolution + ReLU
→ Max Pooling
→ Flatten
→ Fully Connected Layer
→ Output
```

## Evaluation

- Accuracy
- Loss curves
- Confusion matrix
- Test-set performance
- Sample predictions

## Technologies

Python, TensorFlow/Keras or PyTorch, NumPy, Matplotlib.

> This repository is an educational machine-learning project and is not a clinical diagnostic system.
