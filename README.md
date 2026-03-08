# EduPath UAE: AI-Driven Student Academic Pathway Predictor
### CSCI 323 - Modern Artificial Intelligence Project
[cite_start]**University of Wollongong in Dubai (UOWD)** [cite: 1, 2]

## Project Overview
[cite_start]EduPath UAE addresses the challenges of manual academic advising at Sheffield Private School by providing a data-driven, objective recommendation system[cite: 69, 81]. [cite_start]Using machine learning, the system analyzes student performance to streamline decision-making for post-secondary pathways in the UAE[cite: 108, 236].

## Key Features & Methodology
* [cite_start]**Stochastic Data Simulation:** Generated 1,500+ student records with "messy" real-world characteristics (duplicates, missing values, noise) to test system robustness[cite: 45, 155].
* [cite_start]**Automated ETL Pipeline:** Performs data cleaning, median imputation for missing grades, and categorical standardization for UAE institutions[cite: 175, 182].
* **Dual-Stage Machine Learning Architecture:**
    * [cite_start]**Stage 1 (Pathway Prediction):** Predicts qualification for Year 13 vs. University Foundation[cite: 49].
    * [cite_start]**Stage 2 (University Matching):** For Foundation students, recommends the most suitable college from the Top 20 UAE universities[cite: 50, 187].
* **Custom Feature Engineering:**
    * [cite_start]`STEM_Strength`: Aggregated Math and Physics performance[cite: 131, 201].
    * [cite_start]`Academic_Readiness`: A weighted index evaluating core university preparedness[cite: 131, 201].

## Performance & Optimization
* [cite_start]**Algorithm:** Random Forest Classifier (chosen for noise handling and explainability)[cite: 120, 123].
* [cite_start]**Optimization:** Utilized `GridSearchCV` with 5-fold cross-validation to ensure model generalization[cite: 52, 191].
* [cite_start]**Success Metrics:** Evaluated via Accuracy, Precision, Recall, and F1 Score[cite: 112].
* [cite_start]**Key Findings:** Feature Importance Analysis identified Mathematics, Physics, and EmSAT English as the most influential indicators[cite: 225].

## Tech Stack
* [cite_start]**Language:** Python [cite: 136]
* [cite_start]**Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn [cite: 137, 138, 139, 140, 141]
* [cite_start]**Environment:** Jupyter Notebook / Google Colab [cite: 142]

## Team Members
* [cite_start]**Timothy Kyle Valle** (8538797) [cite: 2]
* [cite_start]**Divyesh Sasikumar** (8392493) [cite: 2]
* [cite_start]**Saqib Iftekhari** (8290891) [cite: 2]
* [cite_start]**Disha Gurav** (8331583) [cite: 2]
