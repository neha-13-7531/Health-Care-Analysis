## 🏥 Health Care Data Analysis
**This project explores and analyzes a healthcare dataset to uncover insights into patient demographics, hospital stays, treatments, outcomes, and readmission patterns.**

## 🎯 Objective
- To understand patient data and hospital performance in order to:
- Improve healthcare service quality.
- Reduce readmission rates.

## 📁 Dataset
- Format: Excel (.xlsx)
- Contents: Patient details such as age, gender, length of stay, diagnosis, treatment, outcome, and readmission status.

## 🛠️ Tools & Libraries
- **Pandas** : Data Loading and Data Manipulation.
- **NumPy** : Numerical calculation.
- **Seaborn** : Advanced Visulization.
- **Matplotlib** : Data Visulization.
- **ydata_profiling** : Create Profile Report.

## 🧾 Features
- **Age** : Age of the patient in years.
- **Gender** : Gender of the patient (Male or Female).
- **Length of Stay** : Number of days the patient stayed in the hospital.
- **Diagnosis** : Medical condition or disease diagnosed.
- **Treatment** : Treatment or procedure given to the patient.
- **Outcome** : Final health result (Recovered, Improved, Deceased, etc.).
- **Readmission** : Indicates if the patient was readmitted (Yes or No).

## 🔍 Steps Perform
##  **1.📥 Data Import**
- Load Excel file using read_excel.

## **2.🧹 Data Cleaning**
- Drop the Patient_id  and Treatment column.
- The minimum  age is 0 so we can use random to get random random number for that 0 age.

## **3.📊 Exploratory Data Analysis (EDA)**
**1.Univariate analysis**
- A histogram showed that most patients were between 30 and 60 years old.
- Another plot showed that the majority of hospital stays were short, usually 0 to 5 days.
- A count plot revealed that the gender distribution was fairly balanced.
- A pie chart displayed the percentage of different patient outcomes like "Recovered" and "Improved" and use for Diagnosis column.
- correlation matrix for 'Age' and 'Length of Stay' column.

**2.Bivariate analysis**
- A plot comparing gender and readmission showed that readmissions were slightly different but overall balanced between males and females.
- Another plot showed how different diagnoses were linked to different outcomes.
- A box plot for "Length of Stay" revealed that most patients had short stays and used for age feature.

## 💡 Recommendations

## **1🧓 Age Distribution**
- The age distribution is fairly wide, with a concentration in the 30–60 age range.
- There's a peak around 40–50 years, suggesting middle-aged individuals are the most frequent patients.
 - ✅Recommendation:
   - Focus preventive and chronic care services (e.g., diabetes, hypertension) on the 30–60 age group.

## **2.🏥 Length of Stay**
- The histogram shows most patients have a short hospital stay (0–5 days), with fewer cases beyond 10 days.
- ✅Recommendation:
   - Optimize resources for short-stay treatments and consider offering more outpatient care packages.

## **3.📊 Univariate Analysis – Categorical Variables**
- Top values in Diagnosis, Treatment, and Outcome are clearly dominated by a few categories.
- ✅Recommendation:
   - Focus resources and awareness programs on the most common diagnoses and treatments.

## **4.📊 Pie Chart – Outcome Distribution**
- The pie chart shows distribution of patient outcomes (e.g., Recovered, Improved, Deceased).
- Most patients fall into Recovered or Improved, with a small portion showing worse outcomes.
- ✅Recommendation:
  - While majority outcomes are positive, analyze patterns in the negative outcomes (e.g., department, treatment type, age).
