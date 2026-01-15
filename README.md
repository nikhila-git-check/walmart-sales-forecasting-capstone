# Walmart Sales Forecasting Capstone

**Author:** Nikhila

## Executive Summary
This capstone project focuses on forecasting weekly product sales at Walmart using historical sales data and external factors such as seasonality, holidays, promotions, and economic indicators. Machine learning regression models were developed and evaluated to support improved inventory planning and business decision-making.

## Rationale
Accurate sales forecasting is critical for retail organizations. Poor forecasts can lead to overstocking, increased holding costs, or lost sales due to understocking. By leveraging historical data and machine learning, retailers can better anticipate demand, optimize promotions, and reduce operational inefficiencies.

## Research Question
Can historical Walmart sales data combined with seasonal, promotional, and economic features accurately predict future weekly product sales?

## Data Sources
- Walmart Sales Forecasting Dataset (Kaggle)
- Weekly sales by store and department
- Holiday indicators
- Fuel price, CPI, unemployment rate
- Promotional markdown data

## Methodology
The analysis follows a structured machine learning workflow:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering for seasonality and promotions
- Training multiple regression models
- Model evaluation using RMSE and R²
- Cross-validation and GridSearch hyperparameter tuning

## Results
Tree-based ensemble models, particularly Random Forest and Gradient Boosting, outperformed simpler regression models. These models effectively captured nonlinear relationships and seasonal sales patterns.

## Next Steps
- Incorporate additional external data sources (e.g., regional events)
- Explore time-series models such as ARIMA or LSTM
- Build store- or department-specific forecasting models


## Repository Structure

- README.md  
- Capstone Project_Final Report-WallmartSalesForecasting.docx
- notebooks/  
  - 01_Data_Cleaning_and_EDA.ipynb  
  - 02_Feature_Engineering_and_Modeling.ipynb  
  - 03_Model_Evaluation_and_Results.ipynb  
- data/  
  - raw/ (features.csv, train.csv, stores.csv)  
  - processed/ (walmart_prepared.csv)  

## Final Report

The full nontechnical capstone report summarizing the problem, methodology, findings, and recommendations is available below:

📄 **[Capstone Final Report – Walmart Sales Forecasting](Capstone_Final_Report_Walmart_Sales_Forecasting.docx)**


## Project Structure
- [Notebook 1: Data Cleaning and EDA](notebooks/01_Data_Cleaning_and_EDA.ipynb)
- [Notebook 2: Feature Engineering and Modeling](notebooks/02_Feature_Engineering_and_Modeling.ipynb)
- [Notebook 3: Model Evaluation and Final Results](notebooks/03_Model_Evaluation_and_Results.ipynb)


