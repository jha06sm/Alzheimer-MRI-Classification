# Alzheimer-MRI-Classification
🧠 Dementia Detection using CNN
📌 Overview

This project focuses on MRI-based dementia classification using Convolutional Neural Networks (CNNs). We developed and compared multiple deep learning models, with a special focus on creating a lightweight yet highly accurate architecture.

The final proposed model, Dementia, achieves 99%+ accuracy while maintaining significantly fewer parameters compared to previous models.

🚀 Models Implemented
1️⃣ Baseline CNN Models
Standard CNN architectures with multiple convolutional and dense layers
High parameter count due to large fully connected layers
Achieved strong performance but were computationally expensive
2️⃣ Dementia (Proposed Model) ✅
Optimized lightweight CNN architecture
Reduced number of parameters
Maintains high accuracy (99%+)
Faster training and inference
Suitable for deployment on low-resource systems
🏆 Key Highlights
✅ Accuracy: 99%+
⚡ Lightweight Model: Reduced parameters significantly
🧠 Efficient Feature Extraction using CNN layers
📉 Lower computational cost compared to baseline models
💻 Deployment-friendly (can run on limited hardware)
🧱 Model Architecture (Dementia)
Conv2D + ReLU
MaxPooling
Conv2D + ReLU
MaxPooling
Conv2D + ReLU
MaxPooling
Flatten
Dense Layers
Softmax Output (4 classes)
📊 Classes

The model classifies MRI images into:

Non-Demented
Very Mild Demented
Mild Demented
Moderate Demented
📂 Dataset
MRI-based dementia dataset
Preprocessed and resized images
Balanced class distribution
