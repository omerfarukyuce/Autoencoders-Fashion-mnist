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
- Average SSIM: 0.7122
- Median SSIM: 0.7308
- SSIM Standard Deviation: 0.1399
- Minimum SSIM: 0.1257
- Maximum SSIM: 0.9779

#### 2. 📉 Reconstruction Error
Measures the mean squared error between original and reconstructed images.

**Statistical Results**:
- Mean Error: 0.0133
- Median Error: 0.0110
- Standard Deviation: 0.0088
- Minimum Error: 0.0015
- Maximum Error: 0.0935
## 🔍 Project Outputs and Observations

### 📊 Visualizations
Our project includes the following visualizations:
- Original vs Reconstructed Images Comparison
- SSIM Score Distribution
- Reconstruction Error Analysis
- Best and Worst Reconstruction Investigations

### 💡 Key Insights
1. The autoencoder successfully captures the fundamental features of images.
2. A 64-dimensional encoding space preserves sufficient information to maintain the essence of images.
3. High SSIM scores indicate that reconstructed images are very similar to original images.

## 🚀 Future Research Directions
- Investigate the impact of different encoding dimensions on performance
- Experiment with more complex architectures (CNN-based autoencoders)
- Test similar approaches on different datasets

## 🎨 Potential Use Cases
- Image compression
- Image noise reduction
- Feature extraction
- Dimensionality reduction

## 🛠️ Requirements
- 🐍 Python 3.7+
- 🧠 TensorFlow
- 🔢 Keras
- 📊 NumPy
- 🐼 Pandas
- 📈 Matplotlib
- 🌈 Seaborn
- 🖼️ Scikit-image

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔍 Code And Kaggle Link
Project: [autoencoders-fashion-mnist.ipynb](https://github.com/omerfarukyuce/Autoencoders-Fashion-mnist/blob/main/autoencoders-fashion-mnist.ipynb)

Kaggle: [🧥👜Autoencoders - Fashion MNIST🥾👖](https://www.kaggle.com/code/merfarukyce/autoencoders-fashion-mnist)
