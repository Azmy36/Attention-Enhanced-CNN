# 👁️ Attention Enhanced CNN

This repository implements a **Convolutional Neural Network (CNN) integrated with Self-Attention mechanisms** to improve image classification performance on generalized datasets like **CIFAR-10**.
By incorporating attention, the model can focus on relevant spatial features, boosting accuracy over standard CNN baselines.

> **⚠️ Important:**
> The notebook handles data downloading, preprocessing, model definition, training, and evaluation in a single workflow.

## 📌 Features

- **Self-Attention Mechanism**: Enhances feature extraction by weighing the importance of different spatial regions.
- **Robust Classification**: Designed for multi-class image classification (10 classes).
- **Comparative Analysis**: Can be compared against baseline CNNs to demonstrate the effectiveness of attention.
- **Framework**: Built using **TensorFlow/Keras**.

## 🧠 Model Architecture

### **CNN + Self-Attention**
- **Convolutional Layers**: Extract local features (edges, textures).
- **Attention Module**: Computes an attention map to highlight global dependencies and important regions within the feature maps.
- **Dense Head**: Fully connected layers for final classification.

**Input**: 32x32x3 RGB Images (CIFAR-10 format)
**Output**: Softmax probability distribution over 10 classes.

## 📂 Repository Structure

```
.
├── Self_Attention_CNN_CIFAR10.ipynb   # Model implementation and training loop
└── README.md                          # Project documentation
```

## 📊 Dataset

**Dataset**: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Classes**: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.
- **Size**: 60,000 32x32 color images.

## ⚙️ Installation & Usage

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Azmy36/Attention-Enhanced-CNN.git
    cd Attention-Enhanced-CNN
    ```

2.  **Install dependencies**:
    ```bash
    pip install tensorflow numpy matplotlib seaborn
    ```

3.  **Run the Notebook**:
    Open `Self_Attention_CNN_CIFAR10.ipynb` to execute the training pipeline and view the attention maps.

## 👨‍💻 Author

**Youssef Mohamed Moussa**
- 📧 Email: [youssefazmy36@gmail.com](mailto:youssefazmy36@gmail.com)
