# Car Market Analysis with CarDekho Data

## Problem Statement
The used-car market contains vehicles with different prices, fuel types, transmission types, and usage levels. It is difficult to understand which factors have the greatest impact on a car's selling price. Buyers and sellers need data-driven insights to evaluate a vehicle's fair market value. This project analyzes historical CarDekho data to identify important market trends and pricing patterns, providing meaningful insights that can support better buying, selling, and pricing decisions.

## Project Description
This project focuses on analyzing CarDekho used-car data using data analysis and visualization techniques. The dataset contains information such as car name, manufacturing year, selling price, present price, kilometers driven, fuel type, seller type, transmission, and number of previous owners. The analysis explores relationships between these variables and identifies the major factors influencing used-car prices.

## Dataset
- **Source:** CarDekho Used Car Dataset
- **Rows:** 301 cars
- **Columns:** Car_Name, Year, Selling_Price, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, Owner

## End Users
- **Car Buyers** – to compare cars and identify reasonable prices
- **Car Sellers** – to estimate competitive selling prices
- **Car Dealers** – to understand demand and pricing trends
- **Used-Car Businesses** – to support inventory and pricing decisions
- **Data Analysts/Business Teams** – to derive insights from automobile market data

## Technology Used
- **Python** – Core programming language
- **Pandas** – Data loading, cleaning, and manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced statistical visualizations

## Project Workflow
1. Data Loading and Inspection
2. Data Cleaning (duplicates, missing values)
3. Outlier Detection and Removal (IQR method)
4. Feature Engineering (Car Age, Depreciation %, Age Groups)
5. Exploratory Data Analysis (EDA)
6. Data Visualization
7. Insight Generation

## Key Insights
- Present price is the strongest driver of selling price (correlation ~0.88)
- Car age has only a weak negative effect on selling price
- Kilometers driven shows minimal direct correlation with price
- Cars depreciate by an average of ~36% from their original present price
- Petrol dominates the resale market, followed by Diesel and CNG
- Manual transmission cars are far more common than automatic

## How to Run
1. Clone this repository or download the files
2. Open `car_market_analysis.ipynb` in Google Colab or Jupyter Notebook
3. Upload the dataset CSV when prompted
4. Run all cells to reproduce the analysis and charts

## Files in this Repository
- `car_market_analysis.ipynb` – Full analysis notebook
- `Car_Dekho_DA.csv` – Dataset used
- `README.md` – Project documentation

