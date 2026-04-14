#  CNN Lab Assignment (RGIPT)

This repository contains my complete laboratory assignment for Convolutional Neural Networks (CNNs) as part of a Machine Learning / Deep Learning course.

---

##  Overview

The assignment covers the full deep learning workflow:

* Data loading and preprocessing (MNIST, CIFAR-10)
* Building CNNs from scratch
* Training, tuning, and regularisation
* Model interpretability (Grad-CAM, feature maps)
* Transfer learning and fine-tuning (VGG16)

---

##  Tech Stack

* Python
* TensorFlow / Keras
* NumPy, Matplotlib, Seaborn
* Scikit-learn

---

##  Tasks Covered

### 🔹 Task 1: Environment & Data Pipeline

* Dataset exploration
* Preprocessing and normalization
* Data augmentation

### 🔹 Task 2: CNN from Scratch

* Manual convolution (NumPy)
* LeNet-5 implementation
* Custom CNN design

### 🔹 Task 3: Training & Regularisation

* Optimizer comparison
* Learning rate tuning
* Dropout, BatchNorm, L2 regularization

### 🔹 Task 4: Visualisation & Interpretability

* Filter visualization
* Feature maps
* Grad-CAM heatmaps
* Confusion matrix & classification report

### 🔹 Task 5: Transfer Learning

* VGG16 as feature extractor
* Fine-tuning with gradual unfreezing
* Ablation study
* Benchmark: scratch vs transfer learning

---

##  Key Results

* Transfer learning outperformed training from scratch
* Fine-tuned model achieved the highest accuracy
* Grad-CAM helped interpret model predictions
* Regularisation significantly reduced overfitting

---

##  Files Included

* Jupyter Notebook (`.ipynb`)
* Final PDF report
* Saved plots:

  * dataset_samples.png
  * augmentation_demo.png
  * lenet_sgd_curves.png
  * optimiser_comparison.png
  * confusion_matrix.png
  * tl_frozen.png
  * tl_finetuned.png
  * tl_benchmark.png

---

##  Reproducibility

* Random seed set to 42
* All experiments are reproducible

---

##  Author

**Sourabh Sahu**

---

Note

This project is developed as part of academic coursework. All implementations are written from scratch following assignment guidelines.
