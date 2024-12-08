# Brain Tumor Detection using VGG19

This repository contains a deep learning-based solution for detecting brain tumors from MRI images. The model is built using the VGG19 architecture with transfer learning and fine-tuning.

## Overview

This project aims to classify MRI images into two categories: 
1. **No Tumor** 
2. **Tumor Detected**

The dataset contains MRI images of both categories, which are preprocessed and fed into a pre-trained VGG19 model for classification.

---

## Features

- **Transfer Learning**: Utilizes the VGG19 model pre-trained on the ImageNet dataset.
- **Binary Classification**: Outputs a binary prediction for tumor detection.
- **Visualization**: Displays training accuracy and loss for better interpretability.
- **Preprocessing**: Includes resizing, normalization, and one-hot encoding.

---

## Requirements

Install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt

**Key Libraries Used**
TensorFlow / Keras
NumPy
OpenCV
PIL
scikit-learn
Matplotlib

**Dataset**
The dataset used is organized as follows:
/brain-tumor-detection/
    ├── no/
    ├── yes/


Steps to Run the Project
Clone the repository:


**Copy code**
git clone https://github.com/your-username/brain-tumor-detection.git
cd brain-tumor-detection
Extract the Dataset: Ensure the dataset is extracted to the following path:


**Copy code**
/content/dataset/brain-tumor-detection/
Run the Code: Use a Python environment to execute the script:


## Copy code
python brain_tumor_detection.py
Test a Custom Image: Place the test image in the appropriate directory and modify the file path in the script to predict on custom inputs.

