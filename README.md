# IPL 2024 Match Outcome Prediction

This project was developed as part of my MSc Data Analytics dissertation at Aston University, Birmingham.

The objective of this research was to predict IPL match outcomes using historical IPL data, feature engineering, and machine learning classification models. The project combines sports analytics with machine learning techniques to identify patterns influencing match results and generate predictive insights.

---

## Project Overview

The Indian Premier League (IPL) is one of the most competitive T20 cricket tournaments in the world, where match outcomes are influenced by multiple dynamic factors such as:

- Team performance
- Venue conditions
- Toss decisions
- Player form
- Historical win rates

This project analyses IPL data from 2008–2024 and applies machine learning models to predict match outcomes.

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Models Used

The following machine learning models were implemented and evaluated:

- Random Forest
- Gradient Boosting
- XGBoost
- Logistic Regression
- Support Vector Machine (SVM)

---

## Dataset

The dataset contains:

- Historical IPL match data
- Ball-by-ball delivery data
- Team statistics
- Venue information
- Toss decisions
- Match outcomes

Data range:
- IPL seasons from 2008 to 2024

---

## Feature Engineering

Several features were engineered to improve predictive performance, including:

- Team win rates
- Rolling performance metrics
- Venue-based averages
- Toss impact analysis
- Team historical performance
- Match-specific contextual features

---

## Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. IPL 2024 Predictions

---

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Precision-Recall Curves
- Confusion Matrix

---

## Key Findings

- Random Forest and Logistic Regression delivered the strongest predictive performance.
- Team win rates and venue conditions were among the most influential features.
- Toss decisions showed moderate impact on match outcomes.
- High-scoring venues introduced greater prediction variability.
- Hyperparameter tuning significantly improved model performance.

---

## Project Results

- Achieved approximately 78% prediction accuracy.
- Successfully generated predictions for IPL 2024 fixtures.
- Performed feature importance analysis to improve interpretability.
- Conducted error analysis for venue-based and matchup-specific prediction challenges.

---

## Repository Structure

```text
ipl-match-outcome-prediction/
│
├── README.md
├── ipl_prediction.ipynb
├── dataset.csv
│
└── screenshots/
```

---

## Screenshots

### Feature Importance
![Feature Importance](Feature%20Importance.PNG)

### Confusion Matrix
![Confusion Matrix](Confusion%20Matrix.PNG)

### Toss Decision Impact
![Toss Decision Impact](Toss%20Decision%20Impact.PNG)

### IPL 2024 Predictions
![IPL 2024 Predictions](IPL%20Prediction%202024.PNG)

---

## Future Improvements

Potential future enhancements include:

- Real-time IPL prediction system
- Live score integration
- Player-specific performance metrics
- Deep learning approaches
- Explainable AI (XAI)
- Deployment as a web application

---

## Author

Dheepsaran Vivekananth

- LinkedIn: linkedin.com/in/dheepsaran-vivekananth-1aa3b2151
- GitHub: github.com/dheepsaranv
