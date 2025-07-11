# High School Scoring System for UConn Admissions

This repository contains the capstone project for the Master of Science in Data Science (MSDS) program at the University of Connecticut. Our goal was to build a data-driven scoring system to help the UConn admissions team prioritize out-of-state high schools for recruitment and outreach.

## 📌 Objective

We developed a ranking model to evaluate domestic high schools based on five key factors:

- **Yield rate** (brand power)
- **Applicants’ academic level**
- **Distance to UConn**
- **College-going rate**
- **Estimated family income percentile**

The scoring results help identify high schools that are both strategically valuable and cost-effective to target.

## 🔍 Methodology

Our approach includes:

1. **Data Integration & Cleaning**  
   Merged multiple datasets on `PUBLIC_ID` and selected relevant features.

2. **Feature Engineering**  
   Engineered the five final scoring features from raw student and school data.

3. **Weight Calculation (AHP)**  
   Applied Analytic Hierarchy Process (AHP) to derive subjective weights for the five factors.

4. **Scoring Model (TOPSIS)**  
   Used the Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) to generate final scores for each high school.

5. **Result Analysis**  
   Identified top-ranked high schools with the highest outreach potential based on our scoring mechanism.

## 📈 Outcome

The final scoring system provides a transparent, interpretable, and scalable way for the admissions team to allocate resources efficiently and explore under-targeted markets.

## 📁 Files

- `data/` – Input datasets (excluded due to NDA)
- `Code.ipynb` – Full pipeline including data processing, feature engineering, modeling (AHP + TOPSIS), and result generation
- 
- `final report.pdf` – Full technical report (see [`final report.pdf`](./final%20report.pdf))

## 🤝 Team

- Haoxian Ruan  
- Botao Wang  
- Shubham Rajaram

## 🔒 Disclaimer

This project was conducted under NDA with the UConn Office of Student Life and Enrollment. Data used in this repository is either anonymized or excluded in accordance with confidentiality agreements.
