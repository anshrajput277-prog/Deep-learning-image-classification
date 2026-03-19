🧠 Deep Learning Image Classification (CNN Case Studies)
This repository contains three important case studies based on Convolutional Neural Networks (CNN) for image classification tasks. These projects demonstrate how deep learning models are used to solve real-world problems ranging from simple digit recognition to medical image analysis.

📌 Project Overview
This project includes:

MNIST Digit Recognition
CIFAR-10 Image Classification
Brain Tumor Detection with Grad-CAM
Each case study focuses on:

Data preprocessing
CNN model design
Training and evaluation
Result interpretation
📂 Folder Structure
deep-learning-image-classification/
│
├── mnist/
│   └── mnist_cnn.py
│
├── cifar10/
│   └── cifar10_cnn.py
│
├── brain_tumor_cam/
│   └── brain_tumor_gradcam.py
│
└── README.md
🔹 Case Study 1: MNIST Digit Recognition
Dataset: Handwritten digits (0–9)
Model: CNN
Accuracy: ~98–99%
📌 Key Concepts:

Image normalization
Convolution layers
Feature extraction
🔹 Case Study 2: CIFAR-10 Classification
Dataset: 10 object classes (airplane, car, dog, etc.)
Model: Deep CNN
Accuracy: ~75–85%
📌 Key Concepts:

RGB image processing
Data augmentation
Multi-class classification
🔹 Case Study 3: Brain Tumor Detection + Grad-CAM
Dataset: MRI brain images
Model: CNN + Grad-CAM
Goal: Tumor classification + visualization
📌 Key Concepts:

Medical image analysis
Explainable AI
Heatmap visualization (Grad-CAM)
⚙️ Technologies Used
Python 🐍
TensorFlow / Keras
NumPy
OpenCV
Matplotlib
🚀 How to Run
Clone the repository:
git clone https://github.com/Aryan-rtp/deep-learning-image-classification.git
Navigate to a project:
cd mnist
Run the code:
python mnist_cnn.py
🎯 Key Learnings
CNN is highly effective for image-based tasks
Model performance depends on dataset complexity
Grad-CAM helps in understanding model decisions
Deep learning can be applied to real-world domains like healthcare
📊 Results Summary
Case Study	Accuracy	Complexity
MNIST	High (~99%)	Easy
CIFAR-10	Medium (~80%)	Moderate
Brain Tumor	Variable	High
📌 Future Improvements
Improve accuracy using transfer learning
Deploy models using web apps (Streamlit/Flask)
Use larger medical datasets for better results
👨‍💻 Author
Aryan Raj Pandey B.Tech CSE (AI)

⭐ If you like this project
Give it a ⭐ on GitHub and share it!

