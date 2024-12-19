# Predictive Modeling for EPL 2022-2023 Standings

This project uses machine learning techniques to predict the final standings of the English Premier League (EPL) for the 2022-2023 season. By leveraging historical data from the 2020-2021 and 2021-2022 seasons, the project aims to provide accurate predictions and actionable insights for fans, analysts, and stakeholders.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Data Collection and Preprocessing](#data-collection-and-preprocessing)
4. [Model Selection and Evaluation](#model-selection-and-evaluation)
5. [Visualization](#visualization)
6. [Results](#results)
7. [Future Work](#future-work)
8. [How to Run](#how-to-run)
9. [Acknowledgments](#acknowledgments)

## Project Overview
The goal of this project is to build a predictive model for the EPL standings using historical data. The primary objectives include:
- Providing insights into team performance and standings.
- Comparing the effectiveness of different machine learning models.
- Visualizing team trends and strengths using various charts.

## Features
- **Data-driven insights:** Analysis of historical data to identify key performance indicators.
- **Machine Learning Models:** Implementation of Random Forest Regressor and Linear Regression models for prediction.
- **Visualization:** Radar charts, bar charts, and tree graphs to represent team performance and model decisions.
- **Evaluation Metrics:** Use of Mean Squared Error (MSE) and R-Squared to assess model accuracy.

## Data Collection and Preprocessing
- **Data Sources:** Statistics from the 2020-2021 and 2021-2022 EPL seasons.
- **Dataset Description:**
  - Match statistics.
  - Player statistics.
  - Team statistics.
- **Preprocessing Steps:**
  - Merging datasets into a unified format.
  - Handling missing values.
  - Feature scaling and selection based on correlation analysis.

## Model Selection and Evaluation
- **Models Implemented:**
  - **Random Forest Regressor:** High accuracy (R² ≈ 0.99997, MSE ≈ 0.006).
  - **Linear Regression:** Lower accuracy (R² ≈ 0.98, MSE ≈ 4.56).
- **Key Findings:** Random Forest outperformed Linear Regression in accuracy and error metrics.

## Visualization
- **Radar Charts:** Visualize team strengths and trends over the seasons.
- **Tree Graphs:** Represent decision-making processes in Random Forest.
- **Bar Charts:** Compare predicted vs. actual standings.

## Results
- Predicted Manchester City as the league champion for 2022-2023.
- Identified top six teams: Manchester City, Liverpool, Chelsea, Tottenham, Arsenal, and Manchester United.

## Future Work
- **Data Integration:** Incorporate additional features such as player-specific statistics and real-time updates.
- **Real-Time Predictions:** Build a dynamic system for live EPL predictions.
- **Deployment:** Create a web application or API for broader accessibility.

## How to Run
1. Clone the repository.
2. Install dependencies listed in `requirements.txt`.
3. Run the `SourceCode_Gr_4_Final_ML_2.ipynb` notebook for training and predictions.
4. Visualizations and results will be generated within the notebook.

## Acknowledgments
This project was conducted as part of the Machine Learning and Data Mining II course at the University of Science and Technology of Hanoi. Special thanks to our mentor, Dr. Doan Nhat Quang, for guidance throughout the project.
