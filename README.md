# BrentOilPriceAnalysis

## Overview

This repository contains the analysis of Brent oil prices, focusing on how significant political and economic events influence these prices over the past decade. The objective is to provide actionable insights for investors, analysts, and policymakers using various statistical models and change point analysis.

## Background

The analysis aims to explore the volatility of the Brent oil market and how major events such as geopolitical conflicts, economic sanctions, and OPEC policy changes affect oil prices. The project will utilize statistical modeling techniques to derive insights that can assist in strategic decision-making.

## Objectives

1. **Define the Data Analysis Workflow**:
   - Outline steps for analyzing Brent oil prices.
   - Understand data generation and compilation.
   - Identify model inputs, parameters, and outputs.

2. **Understand the Model and Data**:
   - Familiarize with time series models suitable for analysis.
   - Explain the purpose and application of selected models.

3. **Analyze Brent Oil Prices**:
   - Measure the impact of significant events on price changes.
   - Explore additional factors influencing oil prices, such as economic indicators and technological changes.

4. **Develop an Interactive Dashboard**:
   - Visualize results and allow stakeholders to explore data dynamics.

## Data Collection

Data includes historical Brent oil prices from May 20, 1987, to September 30, 2022, and information on significant events affecting oil prices. Sources include:
- Financial databases
- World Bank
- IMF
- IEA

## Data Preprocessing

The dataset underwent cleaning to handle missing values and outliers. Consistency in date formatting and price representation was ensured.

## Exploratory Data Analysis (EDA)

Visualizations were created to identify trends, correlations, and anomalies in the data, helping to understand the relationships between oil prices and significant events.

## Model Selection and Implementation

The following models were selected for analysis:
- **ARIMA**: For capturing trends and seasonality.
- **GARCH**: To model and forecast price volatility.
- **VAR**: For multivariate analysis including economic indicators.
- **LSTM**: For capturing complex patterns in sequential data.

## Analysis of Results

Model performance was evaluated using metrics like RMSE and MAE. Significant insights regarding the impact of geopolitical and economic events on oil prices were derived.

## Communication of Findings

An interactive dashboard was developed using Flask (backend) and React (frontend) to visualize the analysis results. The dashboard allows stakeholders to explore the correlation between events and Brent oil prices dynamically.

## Expected Outputs and Limitations

### Expected Outputs
- Actionable insights regarding the influence of events on oil prices.
- Predictive analytics for strategic decision-making.

### Limitations
- Data quality and availability may affect results.
- Unforeseen events might lead to outcomes not captured by historical patterns.

## Installation

To get started with the project, clone the repository:

```bash
git clone https://github.com/yourusername/BrentOilPriceAnalysis.git
cd BrentOilPriceAnalysis
```

Install the required packages:

```
pip install -r requirements.txt
```

## Usage 
Run the analysis scripts to generate insights and visualizations. For the dashboard, navigate to the frontend directory and start the React application:

```
cd frontend
npm start
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
