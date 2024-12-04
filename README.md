# 🦠 COVID-19 Detection Using Convolutional Neural Networks (CNN)

This project implements a deep learning model to classify chest X-ray images into **COVID-19** or **Non-COVID-19** categories using a Convolutional Neural Network (CNN).

---

## 🌟 Project Highlights

- **Data Augmentation**: Applied transformations such as rescaling, zoom, and horizontal flip. 📊
- **Custom CNN Model**: Designed a CNN architecture for binary classification. 🤖
- **High Accuracy**: Achieved **97.5% training accuracy** and **93.1% validation accuracy**. 📈
- **Model Deployment Ready**: Saved the trained model for practical use. 💾

---

📊 **Data Overview**

Dataset:

X-ray images categorized into two classes: COVID-19 and Non-COVID-19.

Images resized to 128x128 and converted to grayscale.

Classes: Binary classification (COVID-19, Non-COVID-19).

🤖 **Model Details**

Architecture:

Input Layer: 128x128 grayscale image.

Convolutional Layers: Four convolutional layers with ReLU activation.

Pooling Layers: Max-pooling layers for dimensionality reduction.

Dense Layers: Fully connected layer with 256 neurons.

Dropout: Applied 20% dropout to prevent overfitting.

Output Layer: Sigmoid activation for binary classification.

Loss Function: Binary Cross-Entropy

Optimizer: Adam

🧪 **Model Performance**

Training Accuracy: 97.5%

Validation Accuracy: 93.1%

Loss Trend: Observed convergence within 10 epochs.
