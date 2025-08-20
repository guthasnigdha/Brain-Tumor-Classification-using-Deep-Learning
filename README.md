# Brain-Tumor-Classification-using-Deep-Learning
This project focuses on the detection and classification of brain tumours using deep learning techniques. Specifically, it leverages the EfficientNetB0 architecture to build a robust image classification model capable of identifying different types of brain tumours from MRI images.


**Detection and Classification of Brain Tumour using EfficientNetB0**

This project implements a **deep learning-based brain tumour detection system** using **EfficientNetB0**, a highly efficient convolutional neural network. The model is trained on MRI scan datasets to classify and detect brain tumours with high accuracy.

## 🚀 **Features**
- Preprocessing of MRI brain scan images  
- Transfer Learning with **EfficientNetB0**  
- Training with data augmentation for better generalization  
- Performance evaluation using accuracy, confusion matrix, and classification reports  
- Visualizations of training progress and predictions  

## ⚙️ **Installation & Requirements**
Make sure you have Python 3.8+ installed. Install dependencies using:<br>
pip install tensorflow keras numpy matplotlib scikit-learn opencv-python

## 📊 **Dataset**
MRI images of the human brain categorized into tumour and non-tumour classes.<br>
Dataset should be structured into train, validation, and test directories.

Example structure:<br>
data/<br>
 ├── train/<br>
 │    ├── glioma/<br>
 │    ├── meningioma/<br>
 │    ├── pituitary/<br>
 │    └── no_tumor/<br>
 ├── test/<br>
 └── validation/<br>
If you don’t already have a dataset, you can explore publicly available datasets on Kaggle Brain Tumour MRI Dataset.

## 🏗️ **Model**<br>
Base Model: EfficientNetB0 (pretrained on ImageNet)<br>
Fine-tuning: Last few layers unfrozen for domain-specific learning<br>
Optimizer: Adam<br>
Loss Function: Categorical Crossentropy<br>

## 📈 **Results**<br>
Achieved high accuracy on validation/test sets<br>
Visualizations show strong learning with minimal overfitting<br>
Model predictions correctly classify tumour types in most cases<br>

## 📌 **Future Improvements**<br>
Experiment with EfficientNetB3/B7 for higher accuracy<br>
Deploy as a Flask/Django web app for real-time MRI analysis<br>
Expand dataset with more samples for improved generalization<br>
