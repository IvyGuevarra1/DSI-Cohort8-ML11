# DSI-Cohort8-ML11
# TTC Subway Delay Prediction  
---

## Project Overview

This project analyzes TTC subway delay data (2021–2025) to predict the factors causing delay and high delay incident >5m.  

Our goal is to improve transit reliability by building predictive models that support TTC operations, service planning, and data-driven decision-making.

---

## Business Motivation

Transit delays impact rider satisfaction, operational efficiency, and city mobility.

By predicting factors causing delay and identifying high-delay incidents, this project aims to:

- Improve operational response planning
- Identify high-risk stations, times, and delay causes
- Enhance overall transit reliability

---

## Dataset

**Dataset:** TTC Subway Delay Dataset  
**Time Range:** 2021 – 2025  

### Key Variables
- `Min Delay` (Delay duration in minutes)
- Time as category (i.e Rush hour AM, PM) 
- Station
- Line
- Direction
- Month, Year, Season
- Remove: Vehicle number
- Target: Cause of delay

---

## Business Questions

1. What factors contribute most to significant delays?
2. Can we classify whether a delay will exceed 5 minutes (high-delay incident)?


---

## Analysis Approach

### Classification (Primary ML Focus)
**Objective:** Predict high-delay incidents (>5 minutes)

- Binary target creation
- Address class imbalance
- Models:
   TBC

---

## Project Timeline

**Project Deadline:** Sunday, March 8  
**Machine Learning Focus:** Classification

| Date | Task | Owner |
|------|------|-------|
| 2021–2025 | Reviewing Data | All |
| Saturday, Feb 28 | Data Cleaning | Wendy |
| Monday, March 2 | Exploratory Data Analysis (EDA) | Nicole H |
| Tuesday, March 3 | Feature Engineering / EDA | Ivy |
| TBD | ML Development (Train/Test) | All |
| TBD | Model Selection | All |
| TBD | GitHub Documentation | Nicole Y / Ivy |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Git / GitHub
- Jupyter Notebook

---

## Project Showcase

At the end of the project, we will present:

- Business motivation
- Data exploration insights
- Model performance comparison
- Key recommendations
- Future improvements
