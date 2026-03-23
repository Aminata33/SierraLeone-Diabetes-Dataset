# Sierra Leone Diabetes Dataset

## 📌 Overview

The **Sierra Leone Diabetes Dataset** is a synthetically generated dataset designed to support research in early diabetes prediction using machine learning techniques, particularly in low-resource healthcare environments.

This dataset was developed to simulate realistic clinical patterns relevant to Sierra Leone and similar contexts, providing a benchmark resource for researchers, students, and practitioners.

---

## ⚠️ Important Note

This dataset is **synthetic** and does not contain real patient data. It was generated to reflect plausible medical distributions and relationships observed in diabetes-related studies.

---

## 🎯 Objectives

This dataset is intended to:

* Serve as a **benchmark dataset** for machine learning models
* Support **early diabetes prediction research**
* Enable experimentation in **low-resource healthcare settings**
* Facilitate **federated learning and distributed AI research**
* Encourage reproducible and comparable research outcomes

---

## 📊 Dataset Information

* **Number of Instances:** 600
* **Number of Features:** 10
* **Target Variable:** Outcome (Diabetes diagnosis)

---

## 🧾 Feature Description

| Feature Name             | Description                                      |
| ------------------------ | ------------------------------------------------ |
| Sex                      | Biological sex (0 = Female, 1 = Male)            |
| Pregnancies              | Number of pregnancies                            |
| Glucose                  | Plasma glucose concentration                     |
| BloodPressure            | Diastolic blood pressure (mm Hg)                 |
| SkinThickness            | Triceps skin fold thickness (mm)                 |
| Insulin                  | 2-Hour serum insulin (mu U/ml)                   |
| BMI                      | Body Mass Index (weight in kg/(height in m)^2)   |
| DiabetesPedigreeFunction | Diabetes likelihood based on family history      |
| Age                      | Age in years                                     |
| Outcome                  | Diabetes status (0 = Non-diabetic, 1 = Diabetic) |

---

## ⚙️ Data Characteristics

* Fully **cleaned dataset** (no missing values)
* Structured for **supervised learning tasks**
* Slightly **imbalanced target distribution**, reflecting realistic clinical scenarios
* Compatible with common ML frameworks (Scikit-learn, TensorFlow, PyTorch)

---

## 💡 Potential Use Cases

* Classification model development (Logistic Regression, Random Forest, XGBoost, etc.)
* Model comparison and benchmarking
* Feature selection and importance analysis
* AI applications in healthcare research
* Federated learning simulations in distributed environments

---

## 🧪 Example Usage (Python)

```python
import pandas as pd

# Load dataset
df = pd.read_csv("data/SierraLeone_Diabetes_Dataset.csv")

# Display first rows
print(df.head())
```

---

## 📁 Repository Structure

```
SierraLeone-Diabetes-Dataset/
│── data/
│   └── SierraLeone_Diabetes_Dataset.csv
│── README.md
│── LICENSE
```

---

## 🌍 Research Context

This dataset was created as part of research efforts focused on:

* AI-driven healthcare solutions in Sierra Leone
* Early disease detection using hybrid machine learning models
* Addressing data scarcity in African healthcare systems

---

## 📖 Citation

If you use this dataset in your research, please cite:

**Bah, A. (2025).** *Hybrid Machine Learning for Early Diabetes Prediction in Sierra Leone.*

---

## 🤝 Contribution

Contributions are welcome! You can:

* Propose improvements
* Add benchmark results
* Share trained models

---

## 📜 License

This dataset is released under the MIT License. See the LICENSE file for details.

---

## 👩🏽‍💻 Author

**Aminata Bah**
MSc Software Engineering, Nankai University
Researcher in Artificial Intelligence & Healthcare Systems

---

## 🔗 Links

## 🔗 Links
- GitHub Repository: https://github.com/Aminata33/SierraLeone-Diabetes-Dataset
- Kaggle Dataset: https://www.kaggle.com/datasets/bahamit/sierra-leone-diabetes-dataset

---

## ⭐ Acknowledgment

If you find this dataset useful, please consider starring the repository and sharing it with the research community.
