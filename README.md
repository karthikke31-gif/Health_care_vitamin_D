* **`Enhanced_Vitamin_D_Deficiency_Prediction.xlsx`** → dataset
* **`healthcare_analysis.ipynb`** → your analysis and modeling notebook

# 🩺 Healthcare Data Analysis – Vitamin D Deficiency Prediction

## 📌 Project Overview

This project focuses on **predicting Vitamin D deficiency** using healthcare data.
It combines **data analysis, preprocessing, and machine learning modeling** to identify individuals at risk of deficiency based on lifestyle, demographic, and environmental factors.

The goal is to **transform raw health records into actionable insights** that can aid preventive care and improve public health outcomes.

---

## 📂 Repository Structure

```plaintext
.
├── Enhanced_Vitamin_D_Deficiency_Prediction.xlsx   # Dataset
├── healthcare_analysis.ipynb                       # Jupyter notebook with analysis & modeling
└── README.md                                        # Project documentation
```

---

## 📊 Dataset Description

The dataset contains various **health, lifestyle, and geographical** attributes including:

* **Age**
* **BMI**
* **Sun Exposure (hours/week)**
* **Physical Activity Level**
* **Vitamin D Intake (mcg/day)**
* **Latitude**
* **Deficiency Status** (Target variable)

Source: Internal compilation / simulated dataset for research purposes.

---

## 🛠️ Methodology

1. **Data Loading & Exploration**

   * Handled missing values
   * Checked distributions and data types
     
2. **Feature Engineering**

   * Encoding categorical variables
   * Feature scaling
     
3. **Model Building**

   * Logistic Regression, Random Forest
   * Hyperparameter tuning using GridSearchCV
     
4. **Evaluation**

   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix
     
5. **Insights**

   * Key factors influencing Vitamin D deficiency risk

---

## 📈 Results

* **Best Model:** * Random Forest with 97% accuracy)*
* **Top Influencing Features:** Sun exposure, BMI, Vitamin D intake

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https:/github.com/karthikke31-gif
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook healthcare_analysis.ipynb
```

---

## 📌 Future Improvements

* Include more environmental and genetic factors
* Deploy model as an interactive web app
* Add explainable AI visualizations (e.g., SHAP)

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


