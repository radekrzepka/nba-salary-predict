# NBA Salary Prediction

## Table of Contents

- [NBA Salary Prediction](#nba-salary-prediction)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Key Features](#key-features)
  - [Technologies Used](#technologies-used)
    - [Data Analysis Libraries](#data-analysis-libraries)
    - [Machine Learning Libraries](#machine-learning-libraries)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation and Setup](#installation-and-setup)

## Overview

This project focuses on analyzing NBA player salaries from the 2022-2023 season in relation to their performance statistics. The analysis aims to:

- Visually represent and explore the relationship between player statistics and their salaries
- Investigate correlations between various player metrics and compensation
- Build predictive models to estimate player salaries based on performance statistics
- Identify potentially overvalued and undervalued players in the league

The project uses a comprehensive dataset from Kaggle containing player statistics and salary information for the 2022-2023 NBA season.

## Key Features

- **Data Exploration**: Comprehensive analysis of NBA player statistics and salary distributions
- **Visual Analytics**: Multiple visualizations showing relationships between performance metrics and compensation
- **Top Earners Analysis**: Identification and analysis of top-paid NBA players
- **Age Impact Assessment**: Analysis of how player age affects salary levels
- **Correlation Analysis**: In-depth exploration of which statistics correlate most strongly with salary
- **Predictive Modeling**: Implementation of machine learning models (Linear Regression, KNN, Random Forest) to predict salaries
- **Value Assessment**: Identification of potentially overvalued and undervalued players based on model predictions

## Technologies Used

### Data Analysis Libraries

- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical operations and array handling
- **Matplotlib**: For creating static visualizations and plots
- **Seaborn**: For enhanced statistical visualizations
- **IPython**: For interactive computing and notebook functionality

### Machine Learning Libraries

- **Scikit-learn**: For implementing machine learning algorithms including:
  - Linear Regression
  - K-Nearest Neighbors Regression
  - Random Forest Regression
  - Data preprocessing tools (StandardScaler, train_test_split)
  - Model evaluation metrics (R² score, Mean Absolute Error)

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook/Lab for running the notebook
- Required Python libraries (available in requirements.txt)

### Installation and Setup

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/nba-salary-predict.git
   ```

2. Navigate to the project directory:

   ```
   cd nba-salary-predict
   ```

3. Create and activate a virtual environment (recommended):

   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

4. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

5. Launch Jupyter Notebook to open the analysis file:
   ```
   jupyter notebook main.ipynb
   ```

The notebook contains a detailed step-by-step analysis, including data cleaning, exploratory data analysis, visualization, correlation analysis, and model building for NBA player salary prediction.
