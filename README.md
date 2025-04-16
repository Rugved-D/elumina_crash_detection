# 🚗 Damage Prediction using Machine Learning

This project focuses on building a predictive model to determine whether a vehicle will be damaged or not, using customer demographic and insurance policy-related data. The model is developed and evaluated within a Jupyter Notebook, following standard machine learning workflows.

---

## 📊 Dataset Description

The dataset includes the following columns:

- **Age** – Age of the customer
- **Gender** – Male or Female
- **Driving License** – Whether the customer holds a valid driving license
- **Previously Insured** – Whether the customer was previously insured
- **Vehicle Age** – Age of the vehicle
- **Vehicle Damage** – History of vehicle damage (Yes/No)
- **Annual Premium** – Insurance premium paid
- **Policy Sales Channel** – Channel through which the policy was sold
- **Vintage** – Number of days customer has been associated with the company

> ⚠️ **Note**: The dataset is not included in this repository. Please upload it to the `data/` directory.

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- NumPy & Pandas
- Seaborn & Matplotlib
- Scikit-learn

---

## 🔄 Workflow Overview

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Class distribution
   - Data visualization

3. **Modeling**
   - Logistic Regression
   - Model evaluation (Confusion Matrix, Accuracy, Precision, Recall)

4. **Results**
   - Interpretation of metrics
   - Insights for potential improvements

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/damage-prediction.git
   cd damage-prediction

2. pip install -r requirements.txt

3. Add the dataset to the data/ folder.

4. Launch notebook:
   ```bash
   jupyter notebook damage_prediction.ipynb

