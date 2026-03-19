# 🧠 MNIST Denoising Autoencoder (PyTorch)

A deep learning project that uses a Convolutional Autoencoder to remove noise from MNIST handwritten digit images.

---

## 📌 Overview

This project demonstrates how an autoencoder can learn to reconstruct clean images from noisy inputs.

- Input: Noisy MNIST images
- Output: Denoised (clean) images
- Model: Convolutional Autoencoder
- Framework: PyTorch

---

## 🚀 Features

- Automatic MNIST dataset download
- Adds synthetic noise to images
- Convolutional encoder-decoder architecture
- Trained using reconstruction loss (MSE)
- Visualization of:
  - Original images
  - Noisy images
  - Denoised outputs

---

## 🏗️ Model Architecture

- **Encoder**
  - Conv2D layers with ReLU
  - Downsampling using stride
- **Decoder**
  - ConvTranspose2D layers
  - Upsampling back to original size (28×28)
  - Sigmoid activation for output

---

## 📦 Requirements

Install dependencies:

```bash
pip install torch torchvision matplotlib
