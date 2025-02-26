# AirlineSatisfactionML

## Overview
This project uses machine learning to analyze airline passenger satisfaction. It identifies key factors that influence customer experience and predicts satisfaction based on travel class, inflight services, and boarding efficiency.

## Dataset
The dataset comes from Kaggle:  
[Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

It contains passenger survey responses on their flight experience and satisfaction ratings.

## Repository Contents
- **Raw Data**: Original dataset files from Kaggle.
- **Cleaned Data**: Processed data for analysis.
- **Tableau Data**: Formatted for visualizations.
- **Jupyter Notebook**: Includes EDA and machine learning models.

## Exploratory Data Analysis (EDA)
Visualizations reveal trends in customer satisfaction. Key insights are shared in an interactive dashboard:  
[Tableau Dashboard](https://public.tableau.com/app/profile/audrey.gil5257/viz/ExploringtheLinkBetweenPassengerSatisfactionLoyalty/Dashboard1?publish=yes)

## Machine Learning Models
- **Preprocessing**: Cleaning, handling missing values, encoding, and scaling.
- **Models Used**:
  - Random Forest (96.41% accuracy)
  - Gradient Boosting
  - Logistic Regression (Baseline comparison)
- **Metrics**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

## Key Findings
- **Top Satisfaction Factors**: Online boarding, inflight WiFi, and travel class matter most.
- **Best Model**: Random Forest outperformed other models with 96.41% accuracy.
- **Areas for Improvement**: Faster boarding, better WiFi, and premium service enhancements.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AirlineSatisfactionML.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## License
For educational and research use. Check Kaggle for dataset licensing.

