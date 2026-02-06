# TensorFlow Revision Journey 

Welcome to my personal repository for mastering **Deep Learning** with **TensorFlow** & **Keras**. This project documents my revision path from basic neurons to advanced Computer Vision and NLP models.

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

##  Repository Structure

The repository is organized by levels of complexity, acting as a step-by-step course:

### 🔹 [Level 1: The Basics & CNN Foundations](./Level_1_The_Basics)
Focuses on the fundamentals of Artificial Neural Networks (ANNs), Data Pipelines, and building Convolutional Neural Networks (CNNs) from scratch.
* **Key Concepts:** Tensors, Dense Layers, Conv2D, MaxPooling, Optimizers, and Data Preprocessing (`image_dataset_from_directory`).
* **Projects:**
    * `Tensorflow01.ipynb`: Introduction to Neurons and simple linear regression.
    * `Tensorflow02_with_callbacks.ipynb`: **Fashion MNIST** classification using Deep Neural Networks (DNN) with **Custom Callbacks** to handle overfitting.
    *   **Capstone:** `Level_1_Capstone_Brain_Tumor_MRI.ipynb`: **Multi-Class Brain Tumor Classification**. 
        * Built a custom CNN model achieving **~97% Accuracy**.
        * Diagnoses 4 classes: Glioma, Meningioma, Pituitary, and No Tumor.
        * Features: Data Augmentation, Confusion Matrix Analysis, and **Interactive Prediction Widgets**.

### 🔹 [Level 2: Advanced Computer Vision](./Level_2_Computer_Vision) *(Coming Soon)*
Deep dive into state-of-the-art Computer Vision techniques.
* **Focus:** Transfer Learning (VGG16, ResNet), Fine-Tuning, Object Detection, and Image Segmentation.
* **Goal:** Leveraging pre-trained models to solve complex visual tasks with less data and training time.

---

## 🛠️ Getting Started

To run these notebooks locally, you need to install the following dependencies:

```bash
pip install tensorflow numpy matplotlib pandas notebook ipywidgets
