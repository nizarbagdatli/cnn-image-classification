# CNN Image Classification

This project presents a Convolutional Neural Network (CNN) model for image classification using the Beans dataset.

The project compares a baseline CNN with an improved CNN architecture and evaluates their performance on validation and test data.

---

## Project Overview

- Dataset: Hugging Face `AI-Lab-Makerere/beans`
- Classes: `angular_leaf_spot`, `bean_rust`, `healthy`
- Task: Image classification using CNNs
- Best test accuracy: approximately **84%**

---

## Models

### Baseline CNN
- Simple convolutional neural network
- Best validation accuracy: **0.7820**
- Test accuracy: **0.8203**

### Improved CNN
- Deeper Conv-BatchNorm-ReLU blocks
- Added regularization with dropout and weight decay
- Best validation accuracy: **0.9098**
- Test accuracy: **0.8438**

---

## Key Results

- The improved CNN performed better than the baseline model
- Regularization and deeper architecture improved generalization
- Confusion matrix analysis showed strongest performance on the `healthy` class

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Files

- `AhmetNizar_Bagdatli_VariantC.ipynb` – notebook with model development and training
- `AhmetNizar_Bagdatli_Report.pdf` – project report and results

---

## Dataset

This project uses the public Beans dataset from Hugging Face:
- `AI-Lab-Makerere/beans`

---

## Project Purpose

This project was developed to explore CNN-based image classification and compare a baseline model with an improved architecture.

It demonstrates:
- deep learning fundamentals
- model evaluation
- confusion matrix analysis
- practical experimentation with image datasets

---

## Author

Ahmet Nizar Bağdatlı  
GitHub: https://github.com/nizarbagdatli

## 📊 Results

- Baseline CNN Test Accuracy: 82.03%
- Improved CNN Test Accuracy: 84.38%

The improved model shows better generalization and higher performance on unseen data.
