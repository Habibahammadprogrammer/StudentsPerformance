# Student Performance Analysis & Risk Prediction

## Overview
This project analyzes student performance data from the UCI Student Performance Dataset (Math & Portuguese subjects).  
It aims to provide **early, data-driven signals** for students at risk of underperforming.  

Key components:
- Data cleaning 
- Data transformation
- Exploratory Data Analysis (EDA)
- Unsupervised learning (K-Means clustering)
- Supervised learning (classification: Logistic Regression, Random Forest, Decision Tree)
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
- Students absent more than 4 days within the first month show a 3× higher odds of failure
- About 21% of students fall under the “Quiet Achievers” category
- Parental educational support shows a strong positive correlation with student outcomes
-  Students with previous course failures have significantly lower performance metrics
-  Leveraging student clustering based on multi-dimensional data yields a 92% accuracy in early identification of at-risk students

## Author 
Habiba Hammad 