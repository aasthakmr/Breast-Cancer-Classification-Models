# Breast Cancer Classification (Recall-Focused)

This project compares three machine learning models—**Decision Tree**, **K-Nearest Neighbors (KNN)**, and **Logistic Regression**—on the Wisconsin Breast Cancer dataset. The emphasis is on **maximizing recall** to reduce false negatives, which is critical in medical diagnosis.

---

## 📄 Files
- **Analysis.pdf**: Full report with code, plots, and conclusions.
- **Analysis.html**: Rendered HTML version of the analysis.

---

## 🔑 Key Insights
- **Decision Tree:** Overfits after depth ≥ 4, failing to generalize malignant cases effectively.  
- **KNN:** Optimal performance at `k=4–6`, balancing recall and generalization.  
- **Logistic Regression (L1):** Achieved **99% recall** for malignant tumors (no false negatives), outperforming other models.

---

## 🛠 Tools & Libraries
- Python  
- scikit-learn, numpy, pandas, matplotlib

---

## 📊 Results Snapshot
| Model               | Recall (Malignant) | Accuracy |
|----------------------|--------------------|----------|
| Decision Tree        | 88%               | 89%      |
| KNN (k=5)            | 91%               | 96%      |
| Logistic Regression  | **99%**           | 95%      |
