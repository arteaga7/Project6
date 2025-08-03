# Project6
This project analyzes the information of many different video games of the last 35 years. The dataset contains more than 16500 rows and 11 columns. Visualizations and hypotheses tests are performed.

**Objective:** To make an extensive data cleaning to perform hypotheses tests (Levene and T tests) to make decisions.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of changing the column names, filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, the formal Levene and T tests are performed to determine if the following hypotheses are true:

• Users mean score of Xbox One = Users mean score of PC

• Users mean score of action games = Users mean score of sport games

Finally, some conclusions are given.

🛠️**Libraries used**: Pandas, Matplotlib, NumPy, SciPy.

The Jupyter Notebook is in scripts/project6.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project6.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project6.ipynb.
