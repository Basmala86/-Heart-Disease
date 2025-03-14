# -Heart-Disease
Heart Disease Data Analysis 🫀📊
Overview
This project analyzes heart disease data using NumPy, Pandas, Matplotlib, and Seaborn to gain insights into how different factors contribute to heart disease. The dataset includes medical indicators such as age, cholesterol levels, blood pressure, heart rate, and ECG results.

Dataset Description 📂
The dataset (heart.csv) contains the following key columns:
age – Age of the patient
chol – Cholesterol level (mg/dL)
trestbps – Resting blood pressure (mm Hg)
thalach – Maximum heart rate achieved
restecg – Resting electrocardiographic results
cp – Chest pain type
target – Heart disease indicator (1 = Disease, 0 = No Disease)

Task Breakdown 🔍
1️⃣ Data Loading & Preprocessing (Pandas)
✔ Load and inspect the dataset
✔ Check and handle missing values using mean imputation
✔ Detect and remove outliers in cholesterol (chol)

2️⃣ Numerical Analysis (NumPy & Pandas)
✔ Compute key statistics:
Mean, Median, and Standard Deviation of Cholesterol (chol)
Mean Blood Pressure (trestbps) for patients with and without heart disease
Maximum and Minimum values of Maximum Heart Rate (thalach)
✔ Sorting & Searching:
Sort patients by cholesterol levels
Identify patients with cholesterol > 300 mg/dL
Find patients older than 60 with abnormal ECG (restecg > 0)
✔ Reshape & Split data using numpy.reshape() and numpy.split().

3️⃣ Data Visualization (Matplotlib & Seaborn)
✔ Histogram: Cholesterol distribution
✔ Scatter Plot: Age vs. Maximum Heart Rate
✔ Bar Chart: Patients with and without heart disease
✔ 3D Plot: Relationship between Cholesterol, Age, and Heart Disease
✔ Pie Chart: Distribution of Chest Pain Types (cp)
