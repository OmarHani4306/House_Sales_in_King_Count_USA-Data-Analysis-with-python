# House_Sales_in_King_Count_USA-Data-Analysis-with-python


## Overview
This project focuses on predicting house prices in King County, including Seattle, using historical sales data. The dataset contains various features such as square footage, number of bedrooms, number of floors, and more. The analysis is conducted using Python in JupyterLab.

## Dataset
The dataset includes house sale prices from May 2014 to May 2015. It has been preprocessed to handle missing values and outliers.

**Source:**  
[King County House Sales Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv)

## Features Used
- **price** (Target Variable)
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **sqft_living**: Living area in square feet
- **sqft_lot**: Lot size in square feet
- **floors**: Number of floors
- **waterfront**: Whether the house has a waterfront view (0 = No, 1 = Yes)
- **view**: Number of times the house was viewed
- **condition**: Condition of the house
- **grade**: Construction and design grade
- **sqft_above**: Square footage of interior space above ground
- **sqft_basement**: Square footage of basement space
- **yr_built**: Year the house was built
- **yr_renovated**: Year the house was renovated
- **zipcode**: ZIP code of the house location
- **lat, long**: Geographic coordinates
- **sqft_living15**: Average living space in surrounding houses
- **sqft_lot15**: Average lot size in surrounding houses

## Methodology
1. **Data Preprocessing**
   - Removed unnecessary columns (`id`, `Unnamed: 0`)
   - Handled missing values in `bedrooms` and `bathrooms`
   - Converted categorical values where necessary

2. **Exploratory Data Analysis (EDA)**
   - Used `seaborn` to visualize price distribution, outliers, and correlations.
   - Boxplots for price variations based on waterfront views.
   - Regression plots for feature correlation analysis.

3. **Modeling**
   - Built regression models to predict house prices.
   - Evaluated models using RMSE and R-squared metrics.

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**
- **Jupyter Notebook**

## Results
- **Highest Price Correlation:** `sqft_living` (strongest positive correlation)
- **Outlier Detection:** Waterfront houses tend to have higher price outliers.
- **Regression Insights:** `sqft_above` is positively correlated with price.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/OmarHani4306/House_Sales_in_King_Count_USA-Data-Analysis-with-python.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook and execute the steps.

