# Bank Churn (Attrition) Prediction

## 📌 Project Overview
We see that the data the 10,000+ rows and 23 columns.

The last two columns are unneccesary and can be excluded along with the 'CLIENTNUM' column

Also, we have multiple categorical columns which need to be encoded before being to the model

# Data Pre-processing

We observe the following columns:


*   'Attrition_Flag' & 'Gender' can be BinaryEncoded
*   'Education Level' & 'Income_Category' can be ordinally encoded
*   'Marital_Status' & 'Card_Category' can be onehot encoded



## 🛠️ Installation & Setup
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## 💊 Dataset Details
This project analyzes customer churn in a banking dataset. The dataset includes features such as account balance, transaction history, and customer demographics.

## 🚀 Key Features
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Evaluation
- Predictions & Insights

## 📝 Example Code
```python
#Importing required libraries

import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression
from sklearn.svm im

data = pd.read_csv('/content/BankChurners.csv')
```

## 🔮 Future Improvements
- Enhance feature selection
- Try different ML models
- Deploy as a web app

## 🐄 License
This project is licensed under the MIT License.

