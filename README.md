# predictive-analytics-for-diabetes-detection

### Overview
This repository contains code and resources for developing a predictive model aimed at detecting diabetes within the Pima Indian community using machine learning techniques. The project focuses on leveraging advanced analytics to facilitate early intervention strategies, aligning with public health initiatives such as the CDC's Health Impact in 5 Years (HI-5).

### Intoduction
Diabetes is a pressing public health issue, particularly among the Pima Indian community, which faces disproportionately high rates of the disease. Early detection plays a crucial role in managing diabetes and improving patient outcomes. This project aims to develop a predictive model using machine learning algorithms to identify individuals at high risk of type 2 diabetes.

### Dataset Description
The dataset used in this project is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases and hosted on Kaggle. It includes medical predictor variables such as glucose levels, blood pressure, BMI, and family history, among others. The dataset comprises data from 768 female patients aged 21 years and above.

|Variable | Description |
|-----|-----|
|Pregnancies | Number of times pregnant|
|Glucose | Plasma glucose concentration a 2 hours in an oral glucose tolerance test|
|BloodPressure | Diastolic blood pressure (mm Hg)|
|SkinThickness | Triceps skin fold thickness (mm)|
|Insulin | 2-Hour serum insulin (mu U/ml)|
|BMI | Body mass index (weight in kg/(height in m)^2)|
|DiabetesPedigreeFunction | Diabetes pedigree function|
|Age | Age (years)|
|Outcome | Class variable (0 or 1) 268 of 768 are 1, the others are 0|

### Data Preprocessing

- **Handling Missing Values:** Imputed missing values for Glucose, BloodPressure, SkinThickness, Insulin, and BMI.
- **Scaling:** Normalized the dataset using feature scaling.
- **Data Balancing:** Employed SMOTE to balance the dataset.
- **Splitting the Dataset:** Divided into training (80%) and test (20%) sets.

### Proposed Intervention

The intervention aims to reduce diabetes-related morbidity and mortality through early detection and targeted preventive care. It involves:

- **Target Audience:** High-risk individuals, clinicians, healthcare providers, and community health workers.
- **Data Visualization and Communication Plan:** Implementation of a real-time Tableau dashboard for dynamic data visualization and informed decision-making.
- **Data Engineering Strategy:** A robust data pipeline utilizing MongoDB, Apache NiFi, and Apache Spark for data management, analysis, and visualization.

### Dependencies

- Python 3.11.8
- Pandas
- NumPy
-	Scikit-learn
-	Matplotlib
-	Seaborn
-	XGBoost
-	Tableau (for dashboard visualization)

### Usage

To use the code in this repository:

1.	Clone the repository: git clone https://github.com/surajnihal/predictive-diabetes-detection.git
2.	Install the required dependencies.
3.	Run the main script or notebooks to replicate the analysis and model development.
