# EduPath UAE: AI-Driven Student Pathway & University Recommendation System

### CSCI323 - Modern Artificial Intelligence Project
**University of Wollongong in Dubai (UOWD)**

## Project Overview
EduPath UAE is a dual-stage machine learning solution designed to automate academic advising for high school students in the UAE. The system predicts whether a student should enter a **Direct Entry (Year 13)** pathway or a **University Foundation** program and recommends a top UAE university based on their academic profile.

## Key Features
* **Stochastic Data Generation:** A custom script simulating 1,500+ student records with realistic "messy" data (nulls, duplicates, and noise).
* **Automated ETL Pipeline:** Robust data cleaning, median imputation for missing grades, and standardization of UAE university naming conventions.
* **Advanced Feature Engineering:** * `STEM_Strength`: Aggregated Math and Physics performance.
    * `Academic_Readiness`: A weighted index (70% STEM, 30% Literacy) to gauge university preparedness.
* **Dual-Stage Random Forest:** An optimized ensemble model utilizing `GridSearchCV` and 5-fold cross-validation.

## 📊 Results
* **Model Accuracy:** 63.00% (Achieved via Random Forest Optimization).
* **Optimization:** Hyperparameter tuning confirmed `n_estimators: 200` and `max_depth: 10` as optimal settings.
* **Explainability:** The project includes Feature Importance visualizations to show which subjects (e.g., EmSAT, Math) drive the most impact on student placement.

## Tech Stack
* **Language:** Python 3.x
* **Environment:** Google Colab / Jupyter Notebooks
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 📂 Repository Structure
* `data/`: Contains the RAW and Cleaned CSV datasets.
* `notebooks/`: 
    * `323_data_generator.ipynb`: The synthetic environment creator.
    * `FINAL_CSCI323_ETL_predictionModel.ipynb`: The core