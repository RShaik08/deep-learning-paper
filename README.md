# 🧠 Deep Learning Lab Implementations

This repository contains weekly implementations of core deep learning concepts as part of the lab coursework. It covers neural networks, convolutional models, transfer learning, explainability, and autoencoders with practical experiments and observations.

---

## 📁 Repository Structure

```
Week-03/
Week-04/
Week-05/
Week-06/
Week-07/
Week-08/
Week-09/
Week-10/
Week-11/
report/
```

---

## 🚀 Weekly Breakdown

### Week 03

* Introduction to Neural Networks
* Basic model implementation

### Week 04

* Forward and Backward Propagation
* Gradient computation

### Week 05

* Optimization techniques (SGD, Adam)
* Training neural networks

### Week 06

* Convolutional Neural Networks (CNN)
* Image classification

### Week 07

* Hyperparameter tuning
* Model performance improvement

### Week 08

* Transfer Learning using pre-trained models

### Week 09

* Model evaluation metrics
* Performance analysis

### Week 10

* Explainable AI techniques
* Model interpretability

---

## 🔥 Week 11: Autoencoder Analysis

Implemented and analyzed multiple types of autoencoders on MNIST and KMNIST datasets:

* Undercomplete Autoencoder
* Overcomplete Autoencoder
* Regularized Autoencoder (L1)
* Denoising Autoencoder
* Sparse Autoencoder
* PCA comparison

### 📊 Key Observations

* Overcomplete autoencoder achieved the best reconstruction quality but showed signs of overfitting
* Undercomplete autoencoder compressed data effectively but lost fine details
* Regularization reduced overfitting but impacted reconstruction clarity
* Denoising autoencoder successfully removed noise but produced slightly blurred outputs
* PCA performed the worst due to its inability to capture non-linear relationships
* Increasing encoding dimension (32 → 64) improved reconstruction quality, especially for KMNIST

---

## 🧪 Datasets Used

* MNIST (handwritten digits)
* KMNIST (Kuzushiji-MNIST, Japanese characters via OpenML)

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## 📄 Report

The detailed report including methodology, experiments, and observations is available in the `report/` directory.

---

## 🎯 Key Learning Outcomes

* Understanding of representation learning using autoencoders
* Comparison between linear (PCA) and non-linear models
* Practical experience with model tuning and evaluation
* Hands-on implementation of multiple deep learning architectures

---


## ⭐ Notes

This repository is intended for academic and learning purposes. All implementations are done as part of coursework and experimentation.

---
