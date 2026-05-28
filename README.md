Fenerbahçe Beko EuroLeague Match Analysis
Overview

This project analyzes Fenerbahçe Beko’s performance in the EuroLeague using match-level statistical data from 2002 to 2025.

The focus is on identifying key performance drivers and evaluating the stability of relationships between game statistics and match outcomes using statistical modeling approaches.

Dataset

Match-level EuroLeague data including:

Points scored and opponent points
Home / away indicator
Rebounds (offensive, defensive, total)
Assists, turnovers, steals, blocks
Shooting percentages (2PT, 3PT, FT)
Performance Index Rating (PIR)
Derived variables (+/- and win/loss outcome)
Coaching eras (manually reconstructed)
Methods
Linear regression modeling of point differential (+/-)
Logistic regression for win probability prediction
Correlation analysis of performance metrics
Hypothesis testing (t-test, chi-square, Fisher test)
ANOVA for coaching-era comparison
Outlier detection and model diagnostics
Key Findings
Assists are consistently a strong positive predictor of offensive performance
Home advantage is significant in simple models but less stable in multivariate settings
Coaching changes significantly affect defensive performance (points conceded)
Turnovers and rebounds show weaker direct predictive power than expected
Match outcomes are primarily driven by offensive output and opponent strength
Models
Linear regression for point differential (R² ≈ 0.52)
Logistic regression for win probability (accuracy ≈ 77%)
Model diagnostics confirm stable and interpretable results
Final Model

Combination of linear and logistic regression models provides a robust framework for explaining and predicting team performance across different seasons and coaching eras.

Tools

R, dplyr, ggplot2, data.table, tidyr, car, stats
