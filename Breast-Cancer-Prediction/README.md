
# 🩺 Breast Cancer Prediction using Machine Learning

This project predict whether a breast tumor is malignant or benign using the Breast Cancer Wisconsin (Diagnostic) dataset. The model helps assist in early diagnosis, aiming to improve decision-making in healthcare.

---

## 📌 Project Highlights

- ✅ Data Preprocessing: Standardized input features for better model performance.
- 🧠 Feature Selection: Selected top features using SelectKBest with mutual information.
- 🔍 Model Training: Used multiple classification algorithms including:
  - Logistic Regression
  - K Nearest Neighbor (KNN)
  - Decision Tree
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Random Forest
- 📊 Performance Metrics: Confusion matrix, classification report and accuracy as follows:
  - Logistic Regression      --- 0.96
  - K Nearest Neighbor (KNN) --- 0.96
  - Decision Tree            --- 0.96
  - Support Vector Machine (SVM) --- 0.96
  - Naive Bayes              --- 0.96
  - Random Forest            --- 0.96

---

## 📈 Dataset

- Source: scikit-learn’s built-in Breast Cancer Wisconsin dataset
- Features: 30 numerical features such as radius, texture, smoothness, etc.
- Target: `0` = Malignant, `1` = Benign

---

## 🛠️ Tools & Technologies

- Python 3.x
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

---

## 📌 Future Improvements

- Add GUI for predictions using Tkinter or Flask
- Include real-time data input options
- Explore deep learning models with TensorFlow or PyTorch

