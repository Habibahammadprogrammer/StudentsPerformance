# Student Performance Analysis & Risk Prediction

## Overview
This project analyzes student performance data from the UCI Student Performance Dataset (Math & Portuguese subjects).  
It aims to provide **early, data-driven signals** for students at risk of underperforming.  

Key components:
- Data cleaning 
- Data transformation
- Exploratory Data Analysis (EDA)
- Unsupervised learning (K-Means clustering)
- Supervised learning (classification: Logistic Regression, Random Forest, SVM)
- Model evaluation and Comparison
- Storytelling and Recommendations



---

## Dataset
- Source: [UCI Machine Learning Repository — Student Performance](https://archive.ics.uci.edu/ml/datasets/Student+Performance)  
- Size: 649 rows, 30+ features  
- License: CC BY 4.0  

Available as:
- Fetched automatically via Python `ucimlrepo` helper
- Local CSV files in `/data` folder (optional)

---

## Project Structure
- data/           Raw and processed CSV datasets
- notebooks/      FinalProject.ipynb
- reports/        FinalReport and Data Quality Report
- slides/         PowerPoint explaining findings
- README.md       Project overview and instructions
- requirements.txt Python dependencies

## Installation 
## Installation
1. Clone Repository
```bash
git clone https://github.com/Habibahammadprogrammer/StudentsPerformance.git
cd StudentsPerformance
  
python -m venv venv
venv\Scripts\activate      # Windows
# source venv/bin/activate  # macOS/Linux
pip install -r requirements.txt
```


## Reproducibility 
- The notebook is run from top to bottom 
- If you don't have internet , csv files are available in Data/ folder 

## Key Insights 

## Author 
Habiba Hammad 