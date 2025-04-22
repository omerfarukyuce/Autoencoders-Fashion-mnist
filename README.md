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

### 📏 Performance Evaluation Metrics

#### 1. 📈 Structural Similarity Index (SSIM)
SSIM measures the structural similarity between reconstructed and original images.

**Statistical Results**:
- Average SSIM: 0.7072
- Median SSIM: 0.7252
- SSIM Standard Deviation: 0.1422
- Minimum SSIM: 0.1180
- Maximum SSIM: 0.9857

#### 2. 📉 Reconstruction Error
Measures the mean squared error between original and reconstructed images.

**Statistical Results**:
- Mean Error: 0.0136
- Median Error: 0.0112
- Standard Deviation: 0.0089
- Minimum Error: 0.0017
- Maximum Error: 0.0945
