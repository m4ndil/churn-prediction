# Customer Churn Prediction

A Machine Learning project to predict whether a customer will leave a bank (churn) using data analysis, visualization and predictive modeling.

## Project Overview

Customer churn prediction helps businesses identify customers likely to leave. This project uses the **Churn Modelling dataset** to:

* Analyze customer behavior
* Perform data cleaning and visualization
* Train machine learning models
* Predict customer churn

---

## Dataset

File used:

```
Churn_Modelling.csv
```

Make sure the dataset is placed in the same folder as the notebook or script.

Example folder structure:

```
customer-churn-prediction/
│
├── churn prediction.ipynb
├── Churn_Modelling.csv
├── README.md
```

---

## Features in Dataset

Some important features include:

* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary
* Exited (Target variable)

Target variable:

```
Exited
0 = Customer stayed
1 = Customer left
```

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/m4ndil/customer-churn-prediction.git
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---

## How to Run

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
churn prediction.ipynb
```

Run all cells.

---

## Project Workflow

1. Import libraries
2. Load dataset
3. Data inspection
4. Data cleaning
5. Exploratory Data Analysis (EDA)
6. Feature preprocessing
7. Model training
8. Model evaluation
9. Prediction

---

## Example Visualizations

* Churn distribution
* Churn by gender
* Churn by geography
* Feature correlation analysis

---

## Error Handling for Dataset Path

The project safely loads dataset from the same folder:

```python
import os

DATA_PATH = os.path.join(os.path.dirname(__file__), "Churn_Modelling.csv")
```

---

## Future Improvements

* Add multiple ML models
* Add hyperparameter tuning
* Add model saving/loading
* Deploy using Flask or FastAPI
* Create web interface

---

## License

This project is open-source and free to use.

---
