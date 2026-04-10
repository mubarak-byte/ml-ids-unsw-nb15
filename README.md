# 🔐 Intrusion Detection System with Machine Learning (UNSW-NB15)

## 📌 Overview
This project explores the use of machine learning for intrusion detection using the UNSW-NB15 dataset.

The goal is to understand how different models behave on real-world cybersecurity data and identify their limitations.

---

## ⚙️ What was done

- Implemented *Perceptron* and *Logistic Regression*
- Handled *class imbalance* using class weights
- Performed *feature engineering* using:
  - Byte-based features (sbytes, dbytes)
  - Network behavior (sttl, dttl)
  - Protocol encoding
- Visualized *decision boundaries*
- Evaluated models using:
  - Accuracy
  - Precision / Recall
  - Classification report

---

## 🔍 Key Insights

- High accuracy can be misleading in imbalanced datasets
- Linear models struggle with *non-linearly separable data*
- Feature engineering had a greater impact than model selection
- Network-based features (bytes, TTL) are strong indicators of attack behavior

---

## ⚠️ Limitations

- Data is not linearly separable
- Linear models cannot fully capture complex patterns
- False positives still exist

---

## 🚀 Next Steps

- Explore *nonlinear models*:
  - Random Forest
  - Support Vector Machines (SVM)
- Improve detection performance and reduce false positives

---

## 📊 Dataset

- UNSW-NB15 Intrusion Detection Dataset

---

## 🧠 Author

Built as part of a learning journey into applying machine learning to cybersecurity and adversarial environments