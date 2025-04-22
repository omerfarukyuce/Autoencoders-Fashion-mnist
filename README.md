# 🧥👜Autoencoders - Fashion MNIST🥾👖

## 🎯 Project Objective
This project explores image compression and reconstruction capabilities using deep learning techniques. By working with the Fashion MNIST dataset, we investigate the process of learning and reproducing fundamental image features through an autoencoder architecture.

## 🧠 Methodology

### 📊 Dataset Analysis
- **Source**: Fashion MNIST
- **Total Samples**: 60,000 training, 10,000 testing
- **Image Characteristics**: 28x28 pixel grayscale
- **Classes**: 10 different fashion product categories

### 🏗️ Model Architecture
Our project consists of two primary components:

#### 1. 🔍 Encoder
- Input Layer: 784 neurons (flattened 28x28 image)
- Layer 1: 256 neurons (ReLU activation)
- Layer 2: 128 neurons (ReLU activation)
- Encoding Layer: 64 neurons (ReLU activation)

#### 2. 🔓 Decoder
- Symmetric inverse of the encoder
- Reconstructing original image from encoded representation
- Final layer: Sigmoid activation for pixel value normalization
