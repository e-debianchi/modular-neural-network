# Experimenting with Modularity in Deep Learning

This repository contains the code and documentation for a university project in the course **Neural Networks for Data Science Applications**. The project focuses on building, training, and evaluating neural networks for **3D image classification**, with a particular emphasis on **modularity and early exit strategies** to improve performance and efficiency.

## 🏫 Course Information

Department of Computer, Control and Management Engineering  
Sapienza University of Rome  
**Course:** Neural Networks for Data Science Applications  
**Author:** Emanuele De Bianchi  

## ⚠️ Info

Comments and instructions from the professor are left in order to understand the specific task and better appreciate the work done by the author of the project.

---

## 📁 Project Structure

- `modular_nn.ipynb`:  
  Jupyter notebook containing:
  - Full implementation of the 3D image classification model
  - Modifications to make the architecture modular
  - Integration of early exit branches
  - Training and evaluation routines
  - Visualizations and detailed comments
  - In-depth explanations of each step

## 🎯 Objectives

- Implement a baseline neural network for 3D image classification
- Modify the architecture to be modular and extensible
- Integrate **early exit** strategies to allow predictions at intermediate layers
- Compare performances in terms of:
  - Accuracy
  - Computational cost
  - Inference time

## 📦 Dependencies

Make sure you have the following installed:

- Python 3.8+
- TensorFlow
- TensorFlow Datasets
- Matplotlib

## 📊 Results & Discussion
The notebook includes analysis and visualizations to evaluate how early exit strategies affect the trade-off between speed and accuracy in deep learning models. Conclusions and insights are drawn based on experimental outcomes.