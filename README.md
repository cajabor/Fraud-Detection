# Credit Card Fraud Detection Using Support Vector Machines and Decision Trees  

This project implements a fraud detection system using **Decision Trees** and **Support Vector Machines (SVM)** to identify fraudulent credit card transactions. By leveraging machine learning on an imbalanced dataset, the model improves fraud detection accuracy while minimizing false positives.  

## Watch a Demo  
[Demo](https://drive.google.com/file/d/1_3zOPky5YJf47eeZkUhweac-7MRuFxPJ/view?usp=sharing)  

## Technical Challenges Solved  
- **Handling Imbalanced Data:** Applied resampling techniques and performance metrics to address class imbalance.  
- **Feature Engineering:** Optimized model inputs through data preprocessing, scaling, and selection of key transaction attributes.  
- **Model Optimization:** Tuned hyperparameters to improve detection performance, achieving **96.4% accuracy**.  
- **Comparative Analysis:** Evaluated Decision Tree vs. SVM models, balancing precision-recall trade-offs for real-world fraud detection scenarios.  

## Features  
- **Fraud Detection Models:** Implements Decision Trees and SVM for classification.  
- **Data Preprocessing:** Handles missing values, normalizes transaction amounts, and applies feature selection.  
- **Visualization Tools:** Generates plots for fraud distribution, model comparison, and performance insights.  

## Installation  
Ensure you have Python installed, then install the required dependencies:  

```bash
python3 -m pip install numpy pandas scikit-learn matplotlib seaborn
