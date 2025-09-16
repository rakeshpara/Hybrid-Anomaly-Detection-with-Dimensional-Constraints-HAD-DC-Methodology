# Hybrid Anomaly Detection with Dimensional Constraints (HAD-DC)

HAD-DC is a project for detecting **visual** and **dimensional anomalies** in the MVTec AD **metal_nut** dataset.  
It combines a **convolutional autoencoder** for visual anomaly detection with **camera calibration–based dimensional analysis**, creating a hybrid anomaly score for robust quality inspection.

---

## 🔍 Features
- Autoencoder-based **visual anomaly detection** (scratches, bends, flips, color changes).  
- **Dimensional anomaly detection** using camera calibration parameters.  
- Hybrid scoring with tunable weight `α` to balance visual vs dimensional checks.  
- Evaluation with Accuracy, Precision, Recall, F1-score, and AUC-ROC.  

---

## 📂 Dataset
- **Source:** [MVTec AD Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad)  
- **Category Used:** `metal_nut`  
- Train: normal (`good`) samples only  
- Test: good + anomalies (flip, scratch, color, bent)  

