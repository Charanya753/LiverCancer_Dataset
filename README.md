# Liver Cancer Raw Dataset (Clinical-Style)

## 📌 Overview
This repository contains a **synthetic but medically realistic liver cancer dataset** designed to resemble **raw hospital/EHR data**.

The dataset intentionally includes:
- Human-readable categorical values
- Measurement units
- Missing values and noisy entries

This makes it suitable for **data preprocessing, machine learning, and academic projects**.

---
| Column Name                  | Description                                                                                    |
| ---------------------------- | ---------------------------------------------------------------------------------------------- |
| **Age**                      | Age of the patient in years.                                                                   |
| **Gender**                   | Biological gender of the patient (Male / Female).                                              |
| **BMI**                      | Body Mass Index of the patient, expressed in kg/m².                                            |
| **Alcohol_Intake**           | Average alcohol consumption measured in units per week (may include values like `unknown`).    |
| **Smoking_Status**           | Indicates whether the patient is a smoker (Yes / No).                                          |
| **Hepatitis_B_Status**       | Presence of Hepatitis B infection (Yes / No).                                                  |
| **Hepatitis_C_Status**       | Presence of Hepatitis C infection (Yes / No).                                                  |
| **ALT_Level**                | Alanine Aminotransferase enzyme level in blood, measured in U/L.                               |
| **AST_Level**                | Aspartate Aminotransferase enzyme level in blood, measured in U/L.                             |
| **ALP_Level**                | Alkaline Phosphatase level in blood, measured in U/L.                                          |
| **Bilirubin_Level**          | Total bilirubin concentration in blood, measured in mg/dL.                                     |
| **AFP_Level**                | Alpha-fetoprotein level, a tumor marker associated with liver cancer, measured in ng/mL.       |
| **Cirrhosis_Status**         | Indicates whether the patient has liver cirrhosis (Yes / No).                                  |
| **Diabetes_Status**          | Indicates whether the patient has diabetes mellitus (Yes / No).                                |
| **Liver_Cancer_Possibility** | Probability score (0–1) representing the likelihood of liver cancer based on clinical factors. |


## 📊 Dataset Details

- **Rows:** 60
- **Format:** Excel (.xlsx)
- **Type:** Raw / Unprocessed
- **Target Variable:** Liver_Cancer_Possibility (0.01 – 0.99)

---

## 🧪 Features Included

| Feature | Description |
|------|------------|
| Age | Patient age |
| Gender | Male / Female |
| BMI | kg/m² |
| Alcohol_Intake | units/week (includes "unknown") |
| Smoking_Status | Yes / No |
| Hepatitis_B_Status | Yes / No |
| Hepatitis_C_Status | Yes / No |
| ALT_Level | U/L |
| AST_Level | U/L |
| ALP_Level | U/L |
| Bilirubin_Level | mg/dL |
| AFP_Level | ng/mL |
| Cirrhosis_Status | Yes / No |
| Diabetes_Status | Yes / No |
| Liver_Cancer_Possibility | Probability score |

---

## ⚠ Data Characteristics
- Missing values (empty cells, nulls)
- Inconsistent entries
- Unit-based measurements
- Not ML-ready (requires preprocessing)

---

## 🎯 Use Cases
- Machine Learning projects
- Data preprocessing demonstrations
- Healthcare analytics
- Academic mini / major projects
- Hackathons

---



## 📬 Author
Created by *[Your Name]*  
