# Skin Cancer Detection Using CNN

This repository contains a deep learning upGrad project that applies **Convolutional Neural Networks (CNNs)** to classify skin lesion images into multiple categories (e.g., melanoma, nevus, keratosis, etc.).  

The project demonstrates how to handle **class imbalance, data augmentation, and overfitting/underfitting detection** in medical imaging datasets.

---

## Features
- Data Preprocessing  
- Data Augmentation using **Augmentor**  
- Handling Class Imbalance  
- CNN Model with **TensorFlow/Keras**  
- Dropout Regularization to reduce overfitting  
- Performance Analysis (Training vs Validation)  
- Class Distribution Visualization  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- Augmentor  
- Pandas / NumPy  
- Matplotlib / Seaborn  

---

## Dataset
The dataset contains images of different skin lesion categories such as:  
- Melanoma  
- Nevus  
- Keratosis  
- Basal Cell Carcinoma  
- Squamous Cell Carcinoma  
- Vascular Lesion  
- Dermatofibroma  
- Actinic Keratosis  
- Seborrheic Keratosis  

> ⚠️ Dataset not included in repo. Please use HAM10000 or your own dataset.

---

## Results & Findings
- Applied **data augmentation** to balance classes and increase dataset size.  
- Verified **class distribution** before and after augmentation.  
- Observed signs of **overfitting** in earlier runs, improved by adding Dropout.  
- Class rebalance improved training stability and fairness across categories.  

---

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/Skin-Cancer-Detection-Using-CNN.git
   cd Skin-Cancer-Detection-Using-CNN
   ```
2. Install requirements: 
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Starter_code_Assignment_CNN_Skin_Cancer.ipynb
   ```

4. Run all cells to train and evaluate the model.
