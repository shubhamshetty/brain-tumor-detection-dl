# Brain Tumor Detection using Deep Learning 🧠🩺

This project leverages machine learning and deep learning techniques to detect brain tumors (glioma, meningioma, pituitary) from MRI scans using CNNs (EfficientNet), Random Forest, and SVM.

## 📂 Project Structure
- `notebooks/`: Jupyter Notebook with experiments and visualizations (models, preprocessing, Grad-CAM, etc.)
- `data/`: Info on dataset used (Kaggle source)
- `results/`: Outputs like confusion matrices, Grad-CAM heatmaps
- `report/`: Final project report (PDF)

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

## 🧠 Dataset
- Source: [Kaggle Brain Tumor Dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)
- Classes: Glioma, Meningioma, Pituitary, No Tumor

## ⚙️ Setup
```bash
pip install -r requirements.txt
