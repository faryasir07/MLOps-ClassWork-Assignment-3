# Tyre Classification using Deep Learning

This project is a **deep learning pipeline** that classifies tyre images into two categories:
- **Good**
- **Defected**

The model is built using **PyTorch** and leverages a **pre-trained ResNet50** network.  
The final fully connected layer was replaced and fine-tuned on a custom tyre dataset.

---

## 🚀 Features
- Transfer learning with **ResNet50** pre-trained on ImageNet.
- Fine-tuned on a tyre dataset for binary classification.
- Saves the trained model as `model.pkl` (ignored in Git to follow best practices).
- Simple and reproducible training pipeline.

---

## 📂 Project Structure
tyre-classification-mlops/
│── train.py # Script to train the model
│── requirements.txt # Python dependencies
│── .gitignore # Ignore model/data/env files
│── README.md # Project documentation




