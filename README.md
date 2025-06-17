# 💧 Water Quality Prediction - RMS

> 🧠 Machine Learning-based multi-parameter water quality prediction  
> 📅 Developed during the **AICTE Virtual Internship - June 2025**  
> 🎓 Sponsored by **Shell** & conducted by **Edunet Foundation**

---

## 🌍 Overview

Access to clean water is a **critical global concern**. This project leverages **machine learning** to predict multiple water quality parameters, enabling **early detection of pollution** and promoting timely environmental intervention.

### 📌 Key Goals:
- Predict multiple water quality indicators using supervised ML
- Enable scalable and accurate environmental monitoring

---

## 📊 Predicted Water Quality Parameters

The model predicts the following parameters:

- NH₄ (Ammonium)
- BOD5 / BSK5 (Biochemical Oxygen Demand)
- Colloids
- O₂ (Dissolved Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulfate)
- PO₄ (Phosphate)
- Cl (Chloride)

---

## 🧪 Approach & Methodology

- 🔍 **Data Collection & Preprocessing**
  - Real-world water quality datasets
  - Data cleaning and transformation using Pandas/NumPy

- 🧠 **Modeling**
  - Used `MultiOutputRegressor` wrapped around `RandomForestRegressor`
  - Handled multi-target regression using Scikit-learn pipeline

- 📏 **Evaluation Metrics**
  - R² Score
  - Mean Squared Error (MSE)

> ⚙️ Results showed **acceptable performance across all predicted parameters**.

---

## 🧰 Technologies Used

| Tool / Library     | Purpose                        |
|--------------------|--------------------------------|
| Python 3.12        | Programming Language           |
| Pandas, NumPy      | Data Handling                  |
| Scikit-learn       | Machine Learning Modeling      |
| Matplotlib, Seaborn| Data Visualization             |
| Jupyter Notebook   | Interactive Development        |

---

## 🎓 Internship Details

| Detail            | Description                             |
|------------------|-----------------------------------------|
| **Type**         | AICTE Virtual Internship                |
| **Organization** | Edunet Foundation                      |
| **Sponsor**      | Shell                                   |
| **Duration**     | June 2025 (1 month)                    |
| **Focus Area**   | Machine Learning in Environmental Monitoring |

---


