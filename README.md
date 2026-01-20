# Healthcare-EDA
# Hospital Readmission Analysis - Diabetes Patients

## Overview
Exploratory Data Analysis of hospital readmission patterns for diabetic patients
to identify key factors affecting 30-day readmissions.

## Business Problem
Hospital readmissions cost the US healthcare system $26B annually. Understanding
readmission patterns can help:
- Reduce healthcare costs
- Improve patient outcomes
- Optimize resource allocation

## Dataset
- **Source**: UCI ML Repository - Diabetes 130-US Hospitals (1999-2008)
- **Size**: 100,000+ patient records, 50+ features
- **Target**: 30-day hospital readmission

## Key Findings
1. Overall 30-day readmission rate: 11.2%
2. Age group 70+ has highest readmission rate (12.8%)
3. Patients with prior inpatient visits 2x more likely to be readmitted
4. High medication count (>20) correlates with increased readmission

## Tools Used
- Python 3.x
- Pandas, NumPy (data manipulation)
- Matplotlib, Seaborn (visualization)
- SciPy (statistical testing)

## How to Run
1. Clone this repository
2. Install dependencies: pip install -r requirements.txt
3. Open and run notebooks/diabetes_readmission_eda.ipynb

## Project Structure
See repo structure above

## Future Work
- Predictive modeling using machine learning
- Deep dive into medication effectiveness
- Seasonal readmission pattern analysis
