* **`Enhanced_Vitamin_D_Deficiency_Prediction.xlsx`** → dataset
* **`healthcare_analysis.ipynb`** → your analysis and modeling notebook

# 🧠 Vitamin D Deficiency Prediction using Machine Learning

## 📘 Overview
This project aims to predict whether a patient is **Vitamin D deficient or sufficient** using clinical and lifestyle features.  
The goal is to assist healthcare providers in identifying at-risk patients early — reducing the need for costly diagnostic tests and enabling timely interventions.

---

## 🎯 Objectives
- Predict **Vitamin D Deficiency Status** based on patient data  
- Compare and evaluate multiple machine learning algorithms  
- Identify the most reliable and accurate model through hyperparameter tuning  
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

## 🧹 Steps Involved
1. **Data Cleaning & Preprocessing**  
   - Handled missing values, duplicates, and categorical encoding  
   - Scaled numerical features for uniformity  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized class distribution, feature correlations, and key trends  

3. **Feature Engineering**  
   - Derived meaningful clinical and behavioral features  
   - Encoded the target variable (`Deficiency_Status_Encoded`)  

4. **Model Building & Evaluation**  
   - Trained models: Logistic Regression, Random Forest, XGBoost, and SVM  
   - Evaluated using Accuracy, Precision, Recall, and F1-score  

5. **Hyperparameter Tuning**  
   - Applied `GridSearchCV` for model optimization  
   - Selected the **Support Vector Machine (SVM)** as the final model with ~99.5% accuracy  

---

## 📊 Model Performance (Optimized)

| Model | Optimized Accuracy |
|--------|--------------------|
| Logistic Regression | 0.9992 ⚠️ *(possible data leakage)* |
| Random Forest | 0.9720 |
| XGBoost | 0.9840 |
| **SVM (Selected)** | **0.9955 ✅** |

---

## 🧠 Key Insights
- Dataset showed a **moderate imbalance (71% non-deficient, 29% deficient)**  
- Logistic Regression achieved unrealistically high accuracy, indicating potential **data leakage**  
- **SVM** demonstrated consistent and realistic performance across all metrics  

---

## 🧰 Tech Stack & Skills
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn, XGBoost, SVM  
- **Concepts:** EDA, Feature Engineering, Model Tuning, Classification Metrics  

---

## 🚀 Outcome
Developed a reliable and interpretable ML pipeline that predicts Vitamin D deficiency with **99.5% accuracy**,  
helping improve healthcare decision-making through **data-driven insights**.

---

## 📁 Project Structure

├── data/
│ ├── vitamin_d_data.csv
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_model_training.ipynb
│ ├── 04_model_tuning.ipynb
├── results/
│ ├── model_performance.csv
│ ├── confusion_matrix.png
├── README.md
└── requirements.txt



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

* Deploy model as an interactive web app
* Add explainable AI visualizations (e.g., SHAP)

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


