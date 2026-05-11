# 🔐 KNN vs HLKNN — Phishing Website Detection

**Student:** Baire Gowda | 
**University:** Chanakya University | **Course:** MCA — Machine Learning | **Year:** 2026

---

## 📌 About This Project

This project is an extended study of the **High-Level K-Nearest Neighbors (HLKNN)** algorithm
originally proposed by Al-Hmouz (2023) in MDPI Electronics, Vol.12, Article 3828.

HLKNN improves standard KNN by incorporating a **second-level neighbor analysis**,
making it more robust to noisy data — which is ideal for cybersecurity applications
like phishing detection, spam filtering and fraud detection.

---

## 📊 Results

| Dataset | KNN | HLKNN | Improvement |
|---|---|---|---|
| Iris (Benchmark) | 96.67% | 97.33% | +0.66% |
| Breast Cancer (Medical) | 94.50% | 96.10% | +1.60% |
| 🔐 Phishing Detection (Cybersecurity) | 93.70% | 95.80% | **+2.10%** |

> HLKNN shows the **largest improvement on Phishing data** — confirming it is most effective on noisy cybersecurity datasets.

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `KNN_HLKNN_Phishing_BaireGowda_FINAL BG.ipynb` | Google Colab Notebook — full KNN vs HLKNN implementation |
| `dataset.csv` | UCI Phishing Website Detection Dataset (11,055 samples, 30 features) |
| `KNN_Code_Report_Cybersecurity_Final BG.html` | Full HTML Code Report with visualizations |
| `IEEE_KNN_Cybersecurity_Final BG.pdf` | IEEE Format Extended Research Paper |

---

## 🛠️ Technologies Used

- Python 3
- scikit-learn
- NumPy, Pandas
- Matplotlib, Seaborn
- Google Colab

---

## 🔐 Cybersecurity Application

HLKNN is particularly effective in cybersecurity domains because:
- Phishing/spam data is noisy with overlapping patterns
- Second-level neighbor analysis reduces misclassification
- Accuracy and robustness are critical in security systems

**Use cases:** Phishing Detection | Spam Filtering | Fraud Detection

---

## 📖 Base Paper

Al-Hmouz (2023) — *High-Level K-Nearest Neighbors (HLKNN): A Supervised Machine Learning
Model for Classification Analysis*  
MDPI Electronics, Vol.12, No.18, Article 3828  
DOI: 10.3390/electronics12183828
