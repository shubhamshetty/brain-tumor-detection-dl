# Brain Tumor Detection using Deep Learning 🧠🩺

This project leverages machine learning and deep learning techniques to detect brain tumors (glioma, meningioma, pituitary) from MRI scans using CNNs (EfficientNet), Random Forest, and SVM.

## 📊 Models Used
- ✅ SVM
- ✅ Random Forest
- ✅ CNN (EfficientNetB0)
- ✅ Grad-CAM for explainability

## 📈 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- Grad-CAM Visuals

## 📈 Results Summary
| Model          | Accuracy |
|----------------|----------|
| SVM            | 76%      |
| Random Forest  | 89%      |
| CNN (EffNetB0) | 92.12%   |

Grad-CAM visualizations were used to interpret CNN model predictions.

## 🧠 Dataset
- Source: [Kaggle Brain Tumor Dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)
- Classes: Glioma, Meningioma, Pituitary, No Tumor

## ⚙️ Setup
```bash
pip install -r requirements.txt
