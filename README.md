# Deep Learning Projects - Lung and Colon Cancer Image Classification

This repository contains four deep learning projects for image classification and style transfer, utilizing various neural network architectures like CycleGAN, ResNet, and Self-Attention models. The focus of the projects is to work with lung and colon cancer histopathological images to generate or classify the images.

## Projects Overview

### 1. **CycleGAN for Lung Cancer Image Translation**
   - **Objective**: Using CycleGAN, this model learns to translate lung cancer histopathological images from one domain to another (e.g., from a healthy lung to a cancerous lung).
   - **Key Features**: 
     - Cycle consistency loss
     - ResNet-based generator
     - PatchGAN discriminator
     - Self-Attention blocks to improve feature extraction

### 2. **CycleGAN for Colon Cancer Image Translation**
   - **Objective**: This model applies CycleGAN for style transfer and image translation to map colon cancer images from one domain to another.
   - **Key Features**:
     - Cycle consistency loss
     - ResNet-based generator
     - PatchGAN discriminator
     - Self-Attention mechanism for enhanced feature extraction

### 3. **Self-Supervised Learning with Contrastive Loss**
   - **Objective**: This project implements a self-supervised learning approach using contrastive loss (e.g., SimCLR) to learn useful representations of lung and colon cancer images.
   - **Key Features**:
     - Contrastive loss
     - Data augmentation for better representation learning
     - Suitable for transfer learning applications

### 4. **Discriminator Noise in CycleGAN**
   - **Objective**: This variation of CycleGAN introduces noise to the discriminator inputs to make the model more robust and prevent overfitting.
   - **Key Features**:
     - Discriminator noise for more generalized learning
     - GAN-based architecture for adversarial training
     - Uses self-attention blocks for capturing complex patterns

---

## Installation

To run the Jupyter notebooks, ensure you have the following dependencies installed:

### Requirements

1. **Python** >= 3.7
2. **TensorFlow** >= 2.0
3. **Keras** (if using a separate Keras installation)
4. **NumPy** >= 1.19.0
5. **Matplotlib** (for visualization)
6. **Pillow** (for image processing)
7. **SciPy** (optional, if needed)

### Install the dependencies

Run the following command to install all required dependencies:

```bash
pip install tensorflow numpy matplotlib pillow scipy
