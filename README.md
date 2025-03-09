# Cricket Analytics Using ODI Statistics

## Overview
This project analyzes **ODI cricket statistics** using **data preprocessing, visualization, and machine learning models** to gain insights and predict player performance.

## Features
- **Data Preprocessing:** Handling missing values, cleaning, and transforming data.
- **Data Visualization:** Interactive graphs using **Plotly** to analyze player and team performance.
- **Machine Learning Models:** Predicting "Player of the Match" awards using **Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost**.
- **Feature Importance Analysis:** Understanding key factors influencing player performance.

## Tech Stack
- **Programming Language:** Python 
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-Learn, XGBoost

## Dataset
- **Source:** ODI Cricket Data (CSV format)
- **Attributes:** Player statistics, match performances, runs, wickets, strike rate, matches played, etc.

### Key Files
- `ODI Cricket Statistics and Analysis.ipynb` → Main script for preprocessing, visualization, and modeling.
- `ODI_Cricket_Data.csv` → Raw dataset.
- `README.md` → Project documentation.

## Visualizations
- **Player Performance Analysis:** Runs, wickets, strike rate comparisons.
- **Team Statistics:** Matches won vs. lost.
- **Machine Learning Predictions:** Player of the match forecasting.

## Model Performance
| Model              | R² Score | Mean Squared Error |
|-------------------|---------|------------------|
| Linear Regression | -1.667107    | 0.078372           |
| Decision Tree     | -8.281250    | 0.272727           |
| Random Forest    | -2.318666    | 0.097518           |
| Gradient Boosting | -6.280275   | 0.213929         |
| XGBoost          | -5.784886  | 0.199372           |

## Future Improvements
- **More advanced ML models** like Neural Networks.
- **Player comparison dashboards** for better insights.
- **Live match data integration** for real-time analytics.

## Contributing
Contributions are welcome! Feel free to **fork** this repository, create a feature branch, and submit a pull request.

## License
This project is licensed under @harshitha-g818.
