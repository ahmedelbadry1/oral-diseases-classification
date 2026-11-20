# Oral Diseases Image Classification

End-to-end deep learning project for classifying intraoral images into 6 oral disease categories: **Calculus, Caries, Gingivitis, Hypodontia, Tooth Discoloration, and Ulcer**.

## Pipeline
- Data validation and Exploratory Data Analysis (EDA)
- Stratified Train / Validation / Test split (70% / 15% / 15%)
- Class imbalance handling using balanced class weights
- Data augmentation (`RandomFlip`, `RandomRotation`, `RandomZoom`, `RandomContrast`)
- Custom CNN built from scratch
- Transfer learning & fine-tuning with **MobileNetV2** and **DenseNet121**
- Hyperparameter tuning (learning rate and dropout)
- Evaluation using Classification Report, Confusion Matrix, and Inference Speed
- Interactive web deployment using **Gradio**

## Test Results
| Model | Test Accuracy (%) | Weighted F1 | Inference (ms/img) |
| :--- | :---: | :---: | :---: |
| MobileNetV2 | 88.53% | 0.8869 | 8.11 |
| DenseNet121 | 86.36% | 0.8661 | 23.34 |
| Custom CNN | 73.32% | 0.7362 | 4.67 |

> **Note:** This project is for educational purposes only and is not intended for medical diagnosis.
