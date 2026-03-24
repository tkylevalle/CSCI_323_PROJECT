# EduPath UAE: AI-Driven Student Academic Pathway Predictor
### CSCI 323 - Modern Artificial Intelligence Project
**University of Wollongong in Dubai (UOWD)** 

## Project Overview
EduPath UAE addresses the challenges of manual academic advising at Sheffield Private School by providing a data-driven, objective recommendation system. Using machine learning, the system analyzes student performance to streamline decision-making for post-secondary pathways in the UAE.

## Key Features & Methodology
* **Stochastic Data Simulation:** Generated 1,500+ student records with "messy" real-world characteristics (duplicates, missing values, noise) to test system robustness.
* **Automated ETL Pipeline:** Performs data cleaning, median imputation for missing grades, and categorical standardization for UAE institutions.
* **Dual-Stage Machine Learning Architecture:**
    * **Stage 1 (Pathway Prediction):** Predicts qualification for Year 13 vs. University Foundation.
    * **Stage 2 (University Matching):** For Foundation students, recommends the most suitable college from the Top 20 UAE universities.
* **Custom Feature Engineering:**
    * `STEM_Strength`: Aggregated Math and Physics performance.
    * `Academic_Readiness`: A weighted index evaluating core university preparedness.

## Performance & Optimization
* **Algorithm:** Random Forest Classifier (chosen for noise handling and explainability).
* **Optimization:** Utilized `GridSearchCV` with 5-fold cross-validation to ensure model generalization.
* **Success Metrics:** Evaluated via Accuracy, Precision, Recall, and F1 Score.
* **Key Findings:** Feature Importance Analysis identified Mathematics, Physics, and EmSAT English as the most influential indicators.

## Tech Stack
* **Language:** Python 
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab 

## Team Members
* **Timothy Kyle Valle** (8538797)
* **Divyesh Sasikumar** (8392493)
* **Saqib Iftekhari** (8290891)
* **Disha Gurav** (8331583) 
