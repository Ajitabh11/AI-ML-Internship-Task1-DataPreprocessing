# 🧹 AI-ML Internship Task 1 – Data Cleaning & Preprocessing

## 📌 Internship: Elevate Labs – AI & ML Internship
## 👨‍💻 Task: Data Cleaning & Preprocessing
## 📊 Dataset: Titanic Dataset

---

## 🎯 Objective
The objective of this task is to learn how to clean and preprocess raw data before applying Machine Learning models.  
This includes handling missing values, encoding categorical features, removing outliers, and scaling numerical features.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🔍 Steps Performed

## 1️⃣ Import Libraries
Imported required libraries:
- pandas
- numpy
- matplotlib
- seaborn
- LabelEncoder
- StandardScaler

---

## 2️⃣ Load Dataset
- Uploaded Titanic-Dataset.csv
- Loaded using `pd.read_csv()`
- Displayed first 5 rows

---

## 3️⃣ Basic Data Exploration
- Used `df.info()` to check data types
- Used `df.isnull().sum()` to check missing values
- Observed missing values in:
  - Age
  - Embarked
  - Cabin

---

## 4️⃣ Handling Missing Values

✔ Filled Age column using Median  
✔ Filled Embarked using Mode  
✔ Dropped Cabin column (too many null values)

---

## 5️⃣ Encoding Categorical Variables

✔ Applied Label Encoding on 'Sex' column  
✔ Applied One-Hot Encoding on 'Embarked' column  

Used:
- `LabelEncoder()`
- `pd.get_dummies()`

---

## 6️⃣ Outlier Detection & Removal

✔ Used Boxplot for Age and Fare  
✔ Applied IQR Method to remove outliers  
✔ Removed extreme values from:
- Age
- Fare

---

## 7️⃣ Data Visualization

✔ Survival Count Plot  
✔ Survival by Gender Plot  
✔ Age Distribution Histogram  
✔ Correlation Heatmap  

---

## 8️⃣ Feature Scaling (Standardization)

✔ Applied StandardScaler on:
- Age
- Fare
- SibSp
- Parch  

Transformed numerical features to have:
- Mean = 0
- Standard Deviation = 1

---

## 9️⃣ Final Output

✔ Saved cleaned dataset as:
---

# 📁 Repository Structure
AI-ML-Internship-Task1-DataPreprocessing/
│
├── Titanic-Dataset.csv
├── Cleaned_Titanic.csv
├── data_cleaning.ipynb
├── screenshots/
│ ├── boxplot.png
│ ├── survival_plot.png
│ ├── heatmap.png
│
└── README.md



---

# 📚 Interview Questions & Answers

### 1. What are types of missing data?
- MCAR
- MAR
- MNAR

### 2. How do you handle categorical variables?
Using:
- Label Encoding
- One-Hot Encoding

### 3. Normalization vs Standardization?
- Normalization scales between 0 and 1
- Standardization scales to mean 0 and std 1

### 4. How do you detect outliers?
- Boxplot
- IQR Method
- Z-score

### 5. Why is preprocessing important?
- Improves model performance
- Removes noise
- Handles missing values
- Makes data ML-ready

### 6. One-hot vs Label Encoding?
- Label Encoding → Assigns numeric labels
- One-hot → Creates separate binary columns

### 7. How do you handle data imbalance?
- Oversampling (SMOTE)
- Undersampling
- Class weights

### 8. Can preprocessing affect accuracy?
Yes. Proper preprocessing significantly improves model accuracy.

---

# 🚀 Conclusion

In this task, I successfully cleaned, processed, visualized, and scaled the Titanic dataset.  
The dataset is now fully prepared for Machine Learning model training.

