# Brain-Tumor-Classification-using-Deep-Learning
This project focuses on the detection and classification of brain tumours using deep learning techniques. Specifically, it leverages the EfficientNetB0 architecture to build a robust image classification model capable of identifying different types of brain tumours from MRI images.


**Detection and Classification of Brain Tumour using EfficientNetB0**

This project implements a **deep learning-based brain tumour detection system** using **EfficientNetB0**, a highly efficient convolutional neural network. The model is trained on MRI scan datasets to classify and detect brain tumours with high accuracy.

## 🚀 Features
- Preprocessing of MRI brain scan images  
- Transfer Learning with **EfficientNetB0**  
- Training with data augmentation for better generalization  
- Performance evaluation using accuracy, confusion matrix, and classification reports  
- Visualizations of training progress and predictions  

## ⚙️ Installation & Requirements
Make sure you have Python 3.8+ installed. Install dependencies using:
pip install tensorflow keras numpy matplotlib scikit-learn opencv-python

📊 Dataset
MRI images of the human brain categorized into tumour and non-tumour classes.
Dataset should be structured into train, validation, and test directories.

Example structure:
data/
 ├── train/
 │    ├── glioma/
 │    ├── meningioma/
 │    ├── pituitary/
 │    └── no_tumor/
 ├── test/
 └── validation/
If you don’t already have a dataset, you can explore publicly available datasets on Kaggle Brain Tumour MRI Dataset.

🏗️ Model
Base Model: EfficientNetB0 (pretrained on ImageNet)
Fine-tuning: Last few layers unfrozen for domain-specific learning
Optimizer: Adam
Loss Function: Categorical Crossentropy

📈 Results
Achieved high accuracy on validation/test sets
Visualizations show strong learning with minimal overfitting
Model predictions correctly classify tumour types in most cases

📌 Future Improvements
Experiment with EfficientNetB3/B7 for higher accuracy
Deploy as a Flask/Django web app for real-time MRI analysis
Expand dataset with more samples for improved generalization
