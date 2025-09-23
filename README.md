# Amazon Fashion Product Classification (CNN-based)

## 📌 Project Overview
This project applies **Convolutional Neural Networks (CNNs)** to the task of **automatic fashion product classification**.  
We use the [Amazon Fashion Products Dataset](https://www.kaggle.com/datasets/poorveshchaudhari/amazon-fashion-products/data) to train a deep learning model capable of categorizing clothing items (tops, bottoms, footwear, accessories, etc.).  

The goal is to improve automated product categorization for e-commerce platforms, enabling better search, filtering, and recommendation systems.  

---

**Team Members:**
- Pratham Pathak 
- Khushal Patel  

## 📂 Dataset
We use the **Amazon Fashion Products Dataset** available on Kaggle:  
👉 [Amazon Fashion Products Dataset](https://www.kaggle.com/datasets/poorveshchaudhari/amazon-fashion-products/data)  

---

## ⚙️ Approach
1. **Preprocessing:** Image resizing, normalization, and train/test split.  
2. **Modeling:** CNN-based architecture (with potential experiments using ResNet, EfficientNet, or Vision Transformers).  
3. **Training:** Using cross-entropy loss and optimization via Adam/SGD.  
4. **Evaluation:** Using accuracy, Top-5 accuracy, confusion matrix, and F1-score.  

---

## 📊 Evaluation Metrics
We will evaluate the model with:
- **Top-1 Accuracy** – exact prediction match.  
- **Top-5 Accuracy** – correct label in top-5 predictions.  
- **Confusion Matrix** – class-level breakdown of errors.  
- **Precision, Recall, F1-score (Macro-averaged)** – for class imbalance.  
- **Training/Validation Curves** – monitor convergence and overfitting.  
