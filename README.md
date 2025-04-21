# Predictive Modeling for Effective Diabetes Treatment and Readmission Reduction

## 📌 Project Objective

This project aims to analyze patient data from **130 US hospitals over a 10-year period** to:

- Identify the most effective **treatments for diabetes**.
- Build a **predictive model** to determine which patients are **less likely to be re-admitted** after receiving certain treatments.
- Support healthcare providers with **data-driven decisions** to enhance patient care and reduce hospital readmissions.

---

##  Why This Project?

###  Problem Significance
- Diabetes is a chronic condition affecting millions, leading to frequent hospitalizations.
- **Hospital readmissions** are costly and often indicate inadequate treatment or care planning.
- By identifying effective treatments, we can reduce readmission rates and improve patient outcomes.

### Real-world Impact
- **Improve Patient Care**: Enable personalized and effective treatment plans.
- **Reduce Costs**: Minimize unnecessary hospital visits and readmissions.
- **Support Clinical Decisions**: Offer predictive insights to healthcare professionals.

---

## Project Methodology

###  Dataset
- Real-world data from **130 hospitals**, spanning **10 years**.
- Features include: patient demographics, diagnoses, medications, procedures, lab results, and readmission status.

###  Steps Followed

1. **Data Preprocessing**
   - Removed duplicates, handled missing values.
   - Encoded categorical variables and filtered diabetes-related cases.

2. **Exploratory Data Analysis (EDA)**
   - Visualized patient distributions and treatment outcomes.
   - Identified patterns and correlations between treatments and readmissions.

3. **Feature Engineering**
   - Created derived features: `inpatient_visits`, `medication_change`, `length_of_stay`, etc.
   - Labeled readmission as: `within 30 days`, `after 30 days`, or `never`.

4. **Model Building**
   - Applied classification models:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Target variable: `readmission status`.

5. **Model Evaluation**
   - Metrics used: **Accuracy, Precision, Recall, F1-score, ROC-AUC**.
   - Performed cross-validation and hyperparameter tuning.

6. **Insights & Recommendations**
   - Identified treatments that correlate with **low readmission rates**.
   - Recommended treatment protocols based on predictive insights.

---

##  Outcome

- Successfully trained a model to predict patient readmission likelihood.
- Gained actionable insights on effective treatments for diabetes.
- Demonstrated how **machine learning** can assist in improving healthcare systems and patient well-being.

---

##  Tech Stack

- **Languages**: Python, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: Scikit-learn, XGBoost
- **Tools**: Jupyter Notebook, Git

---

##  Future Work

- Include more recent or real-time patient data.
- Deploy the model as a REST API for hospital decision support systems.
- Expand to other chronic diseases for treatment analysis.

---

##  Author

**Ashish Raj**    
GitHub: [ashishraj987](https://github.com/ashish570raj)

---

