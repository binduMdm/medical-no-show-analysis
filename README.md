# Medical Appointments – Data Cleaning & Analysis

## Project Overview

This project explores patient no-show behavior using a dataset of 110,000+ medical appointments in Brazil. It involves end-to-end data cleaning, feature creation (like waiting time), and exploratory visualizations. The goal is to identify what factors — like age, gender, waiting time, or SMS reminders — may influence whether a patient misses their appointment.

This dataset is commonly used in data science interviews and bootcamps. The code is beginner-friendly but follows best practices in naming, structure, and readability.
---

## Problem Statement

Every missed medical appointment creates delays, wasted resources, and financial loss. By analyzing a dataset of over 110,000 appointments, this project aims to answer:

- Who is more likely to miss their appointment?
- Does age or gender matter?
- Do reminders (SMS) actually help?
- Does the wait time between scheduling and appointment day influence attendance?

---

## What I Did

### Data Cleaning
- Removed negative ages and duplicate rows
- Standardized column names (fixed typos like hipertension)
- Converted date columns and calculated waiting_days
- Transformed no_show into binary (0 = showed up, 1 = missed)
- Exported the cleaned dataset for further use

### Exploratory Data Analysis
Used seaborn and matplotlib to visualize patterns and trends

---

## Key Insights from EDA

- Over 80 percent of patients did show up for their appointments
- Female patients had more appointments but also slightly more no-shows
- Middle-aged adults (36–55) missed the most appointments
- Patients with longer waiting days were more likely to miss
- Those who received SMS reminders missed less frequently
- No strong linear correlations found, which makes this a good case for machine learning models later

---

## Tools Used

Python — pandas, numpy, matplotlib, seaborn  
Jupyter Notebook — for interactive exploration  
CSV — raw and cleaned data files



