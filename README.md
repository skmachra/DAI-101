# Vehicle Price Analysis

## Author
- **Sunil Kumar**

📌 Note: Ensure a stable internet connection for smooth execution of the notebook. 🔄📶

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset containing vehicle listings. The goal is to analyze price distributions, identify missing values, and visualize key patterns in the dataset.

## Dataset Overview
The dataset contains various attributes of used vehicles, including:
- **Vehicle Details**: `vehicleType`, `brand`, `model`, `gearbox`, `fuelType`
- **Pricing & Registration**: `price`, `yearOfRegistration`, `monthOfRegistration`
- **Usage & Condition**: `odometer`, `notRepairedDamage`, `lastSeen`
- **Other Features**: `offerType`, `seller`, `abtest`, `powerPS`

## Data Cleaning & Preprocessing
- Identified and handled missing values in `vehicleType`, `gearbox`, `model`, `fuelType`, and `notRepairedDamage`.
- Converted price values from string format (`$xx,xxx`) to numerical format.
- Checked for duplicate records and removed them if necessary.

## Exploratory Data Analysis (EDA)
### 1. **Univariate Analysis**
- **Price Distribution**: Identified outliers and price trends.
- **Vehicle Type Distribution**: Box plots to compare price variations.
- **Fuel Type & Gearbox Trends**: Bar charts for insights.

### 2. **Bivariate Analysis**
- **Price vs. Vehicle Type**: Box plots showing how prices vary across types.
- **Price vs. Year of Registration**: Scatter plot to analyze depreciation trends.
- **Correlation Analysis**: Heatmap to detect relationships among variables.

### 3. **Key Insights**
- Certain vehicle types (e.g., SUVs, limousines) tend to have higher median prices.
- Some categories contain significant missing values, requiring imputation.
- Older vehicles generally have lower prices, but classic models may be exceptions.
- Diesel vehicles tend to have a higher price range compared to petrol vehicles.