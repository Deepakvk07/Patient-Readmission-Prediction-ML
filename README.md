# 🏥 Hospital Readmission Predictor  
### Healthcare Risk Scoring using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# 📌 Project Overview

Hospital readmission is one of the major challenges in healthcare systems. Patients who are discharged from hospitals may require re-admission within a short period due to complications, improper diagnosis, or ineffective treatment plans.

This project develops a **Machine Learning-based Hospital Readmission Predictor** to identify whether a patient is likely to be **readmitted within 30 days after discharge** using patient demographics, medical history, diagnoses, medications, and hospital-related information.

The objective of this system is to assist healthcare institutions in:

✔ Reducing avoidable readmissions  
✔ Improving patient care quality  
✔ Supporting medical decision-making  
✔ Enhancing healthcare risk assessment  

This project demonstrates a **real-world healthcare analytics use case** commonly used in **predictive analytics and clinical risk modelling**.

---

# 🎯 Problem Statement

Hospital readmissions are expensive and often indicate poor treatment outcomes. Predicting high-risk patients before discharge can help hospitals provide additional medical attention and preventive care.

The problem addressed in this project:

> **Can Machine Learning predict whether a discharged patient will be readmitted within 30 days?**

---

# 🗂 Dataset Information

### Dataset Used
**Diabetes 130-US Hospitals Dataset (1999–2008)**

This dataset contains over **100,000 hospital records** collected from **130 US hospitals** over a 10-year period.

### Dataset Features Include:

- Patient Age
- Gender
- Race
- Admission Type
- Medical Specialty
- Diagnoses
- Number of Lab Procedures
- Number of Medications
- Time in Hospital
- Number of Diagnoses
- Previous Admissions
- Insulin Information
- Diabetes Medication Details

### Target Variable

**Readmitted**

Values:

| Value | Meaning |
|--------|----------|
| `<30` | Readmitted within 30 days |
| `>30` | Readmitted after 30 days |
| `NO` | No readmission |

For this project:

- **1 → Readmitted within 30 days**
- **0 → Not readmitted**

### Dataset Source

https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

---

# 🧠 Machine Learning Workflow

The project follows a complete Machine Learning pipeline:

```text
Data Collection
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Exploratory Data Analysis (EDA)
       ↓
Feature Encoding
       ↓
Data Visualization
       ↓
Feature Selection
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction System
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Google Colab | Development Environment |
| Pandas | Data Processing |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |

---

# 📊 Exploratory Data Analysis (EDA)

Several visualisations were performed to understand the dataset and identify useful insights.

### Implemented Visualisations

✅ Missing Values Heatmap  
✅ Readmission Distribution  
✅ Gender Distribution  
✅ Age Group Analysis  
✅ Top Diagnoses Analysis  
✅ Correlation Heatmap  
✅ Confusion Matrix  
✅ Feature Importance Graph

---

# 🤖 Machine Learning Model

### Model Used

**Random Forest Classifier**

Why Random Forest?

- Handles large datasets efficiently
- Works well with healthcare data
- Handles non-linear relationships
- Reduces overfitting
- Provides feature importance scores

---

# 📈 Model Evaluation Metrics

The following metrics were used:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help evaluate how effectively the model predicts patient readmission risk.

---

# 📁 Project Structure

```text
Hospital-Readmission-Predictor/
│── Hospital_Readmission_Predictor.ipynb
│── diabetic_data.csv
│── requirements.txt
│── README.md
│── images/
│   ├── readmission_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
```

---

# 🚀 How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/Hospital-Readmission-Predictor.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Open Notebook

Open in:

- Google Colab
OR
- Jupyter Notebook

### Step 4: Run All Cells

Upload the dataset file:

```text
diabetic_data.csv
```

Then execute all notebook cells.

---

# 📌 Key Insights

- Certain diagnosis patterns strongly influence readmission probability.
- Previous hospital admissions increase risk.
- Medication and hospital stay duration contribute significantly to prediction.
- Feature importance analysis helps identify critical healthcare factors.

---

# 🔮 Future Improvements

Planned improvements:

- Hyperparameter Tuning
- XGBoost Model
- Deep Learning Implementation
- Explainable AI (XAI)
- Healthcare Dashboard
- Model Deployment

---

# 💼 Real-World Applications

This project can be useful for:

🏥 Hospitals  
🩺 Healthcare Providers  
📊 Clinical Risk Analytics  
💡 Medical Decision Support Systems  
📈 Predictive Healthcare Analytics  

---

# 👨‍💻 Author

**Deepak Vishwakarma**

### Connect with Me
- LinkedIn: Add your LinkedIn profile
- GitHub: Add your GitHub profile

---

# ⭐ Support

If you found this project useful, consider giving it a **star ⭐** on GitHub.
