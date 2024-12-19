# Generative Adversarial Networks (GANs)

This repository contains the implementation and experiments for **Training DCGANs (Deep Convolutional GANs)**, developed as part of the ADRL (Advanced Deep Reinforcement Learning) course assignment. The project explores the training of GANs for generating high-quality images and incorporates techniques for runtime data augmentation and adaptive training strategies.

## Features

- **GAN Training**: Implements DCGAN with PyTorch for generating images.
- **Runtime Augmentation**: Includes a custom class for adaptive augmentation during training, featuring:
  - Brightness adjustment (increase/decrease).
  - Saturation enhancement.
  - Sharpness enhancement.
  - Transformations like random rotation, affine shear, and perspective distortion.
- **Adaptive Probability Adjustment**: Dynamically adjusts augmentation probability based on discriminator loss differences.

## Project Structure

- **GAN Architecture**:
  - Generator and Discriminator models implemented using PyTorch.
  - Training script for optimizing adversarial loss.
- **Augmentation**:
  - Adaptive augmentation class that enhances image diversity during training to improve GAN robustness.
- **Evaluation**:
  - Visualization of generated samples during and after training.
  - Metrics for assessing the quality of generated images.

## Requirements

- Python 3.8+
- PyTorch 1.13+
- torchvision
- Matplotlib
- OpenCV
- NumPy
- Pandas
