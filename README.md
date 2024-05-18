# Systemic Crisis Prediction in Africa

## Introduction

This project involves working on the 'Systemic Crisis, Banking Crisis, Inflation Crisis in Africa' dataset provided by Kaggle. The objective is to develop a machine learning model to predict the likelihood of a systemic crisis emergence given a set of economic indicators such as annual inflation rates.

## Problem Statement

The main goal of this project is to predict the likelihood of a systemic crisis in African countries based on historical economic indicators. This involves analyzing a dataset that includes various types of crises (banking, debt, financial, inflation, and systemic crises) from 1860 to 2014 across 13 African countries.

## Dataset Description

The dataset focuses on different types of crises that occurred in 13 African countries: Algeria, Angola, Central African Republic, Ivory Coast, Egypt, Kenya, Mauritius, Morocco, Nigeria, South Africa, Tunisia, Zambia, and Zimbabwe. The key objective is to predict the likelihood of a systemic crisis using indicators such as annual inflation rates.

### Features

- **country_number**: Integer, a unique identifier for each country.
- **country_code**: String, ISO code of the country.
- **country**: String, name of the country.
- **year**: Integer, the year of the data record.
- **systemic_crisis**: Binary, indicates the presence of a systemic crisis (1 = yes, 0 = no).
- **exch_usd**: Float, exchange rate of the local currency against USD.
- **domestic_debt_in_default**: Binary, indicates domestic debt default status.
- **sovereign_external_debt_default**: Binary, indicates sovereign external debt default status.
- **gdp_weighted_default**: Float, GDP weighted default.
- **inflation_annual_cpi**: Float, annual inflation rate based on Consumer Price Index (CPI).
- **independence**: Binary, indicates whether the country is independent.
- **currency_crises**: Binary, indicates the presence of a currency crisis.
- **inflation_crises**: Binary, indicates the presence of an inflation crisis.
- **banking_crisis**: Binary, indicates the presence of a banking crisis.

## Objective

The primary objective of this project is to develop a linear regression model to predict the likelihood of a banking crisis using the given features. The target variable is `banking_crisis`.

## Tools and Libraries

This project utilizes the following tools and libraries:
- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning modeling.
- **Matplotlib/Seaborn**: For data visualization.

## Installation

To get started with the project, you need to have Python installed. Install the necessary libraries using pip:

```sh
pip install pandas scikit-learn matplotlib seaborn
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/Oluwaseun/Systemic_African_Crises.git
cd Systemic_African_Crises
```

2. **Run the analysis script:**

The main analysis and modeling are contained in the `analysis.py` script. Run this script to perform the data analysis and train the machine learning model:

```sh
python analysis.py
```

## Analysis and Model Development

### Data Preprocessing

- **Cleaning**: Handle missing values and correct any inconsistencies in the dataset.
- **Encoding**: Convert categorical variables into numerical values.
- **Scaling**: Standardize the numerical features to improve model performance.

### Model Training

- **Linear Regression**: Implement a linear regression model to predict the `banking_crisis`.
- **Evaluation**: Use appropriate metrics (e.g., R² score, Mean Squared Error) to evaluate the model's performance.

### Results and Insights

- **Feature Importance**: Analyze which features have the most significant impact on the prediction of banking crises.
- **Predictive Accuracy**: Assess the accuracy and reliability of the model in predicting banking crises.

## Recommendations

- **Economic Policies**: Suggest economic policies that can help mitigate the risk of banking crises based on the model's findings.
- **Further Research**: Recommend areas for further research to improve the model's accuracy and predictive power.

## Conclusion

By developing a robust machine learning model and analyzing the key economic indicators, this project aims to provide valuable insights into the factors contributing to systemic crises in African countries, enabling better preparedness and response strategies.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank Kaggle for providing the dataset and the open-source community for the tools and libraries used in this project.
