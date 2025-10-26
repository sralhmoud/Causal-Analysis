# 🧠 Causal Analysis of Osteoporosis Dataset  
Exploring causal relationships between medical and lifestyle factors affecting osteoporosis using data-driven inference techniques.  

---

## 🎯 Overview  
Osteoporosis is a chronic condition characterized by reduced bone density and an increased risk of fractures.  
This project applies **causal inference** methods to investigate potential cause-and-effect relationships between clinical and lifestyle variables that may contribute to the onset of osteoporosis.  
The analysis goes beyond correlation to identify possible causal pathways that could inform prevention and early intervention.  

---

## 🧩 Objectives  
- Understand how causal inference differs from traditional correlation analysis.  
- Identify variables that have a direct or indirect effect on osteoporosis risk.  
- Apply causal discovery and estimation techniques to real-world medical data.  
- Evaluate model robustness and interpretability using statistical visualization tools.  

---

## ⚙️ Methods & Techniques  
- **Approach:** Exploratory data analysis → Confounder detection → Causal graph construction → Effect estimation  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, DoWhy, CausalInference, StatsModels  
- **Statistical Methods:**  
  - Correlation analysis for initial feature screening  
  - Graph-based causal modeling  
  - Average Treatment Effect (ATE) estimation  
  - Regression-based causal validation  
- **Environment:** Jupyter Notebook  

---

## 📊 Dataset  
The dataset includes demographic, clinical, and lifestyle attributes related to osteoporosis risk factors.  
Preprocessing included missing-value handling, outlier detection, normalization, and categorical encoding.  

---

## 📈 Results & Insights  
- Discovered significant causal effects between **Age**, **Calcium intake**, and **Bone Density Score (BMD)**.  
- Lifestyle variables such as **Exercise frequency** and **Dietary habits** showed measurable indirect influence.  
- The estimated **Average Treatment Effect (ATE)** supports the hypothesis that calcium and activity level have protective causal effects against bone loss.  
- Findings highlight the importance of preventive habits and early screening for high-risk groups.  

---

## 🛠 Tools & Technologies  
| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy, Seaborn, Matplotlib |
| Causal Inference | DoWhy, CausalInference, StatsModels |
| Environment | Jupyter Notebook |
