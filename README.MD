# *Real Estate Data Analysis in Oman*

This project focuses on scraping, cleaning, integrating, and modeling real estate property data from two popular Omani listing websites: OpenSooq and Hilal Properties. The goal is to generate insights, engineer meaningful features, and predict property prices based on available data.
.
├── data/
│   ├── opensooq_data.csv
│   ├── hilal_data.csv
│   └── combined_cleaned_data.csv
├── notebooks/
│   └── real_estate_analysis.ipynb
├── README.md

## Objectives
Scrape real estate listings from om.opensooq.com and hilalproperties.com.

Clean and merge both datasets into a unified structure.

Engineer features like price per square meter, number of rooms, etc.

Build a Linear Regression model to predict prices.

Evaluate model performance using MAE, RMSE, and R² Score.

## Features Used
Size (area in sqm)

Rooms (number of rooms or bedrooms)

Location

Listing Type (rent/sale)

Price per m²

Is Expensive (flag indicating high-value properties)

## Model Details
Model Used: Linear Regression

Accuracy (R²): ~0.70 (depending on the data quality and preprocessing)

## Tools & Libraries

Python 3.x

Pandas, NumPy

BeautifulSoup, requests (for web scraping)

Scikit-learn (for modeling)

Matplotlib, Seaborn (for visualization)

## How to Run
Clone the repository.

Install the required libraries:
pip install -r requirements.txt

Open the notebook:
jupyter notebook notebooks/real_estate_analysis.ipynb

Run all cells to perform data scraping, cleaning, feature engineering, and modeling.

## Notes
Some listings may have missing or inconsistent data; these are handled during the cleaning step.

You can extend the model using more advanced regressors like RandomForestRegressor or XGBoost.

## Contributing
Feel free to fork this repository, raise issues, or submit pull requests if you'd like to improve the model, add new features, or scrape more websites.







