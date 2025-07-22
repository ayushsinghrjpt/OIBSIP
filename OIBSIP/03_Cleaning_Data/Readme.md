# 🧹 NYC Airbnb Data Cleaning & EDA

This project involves cleaning and exploring the **New York City Airbnb 2019** dataset. It includes detecting and handling missing data, removing outliers using the IQR method, and visualizing key patterns using boxplots.

## 📌 Objectives

- Understand the structure and quality of the data
- Handle missing values
- Remove invalid and extreme values (outliers)
- Visualize distributions of numerical features
- Prepare clean data for future analysis or modeling

## 🧰 Tools & Libraries

- Python 3.x
- `pandas`
- `matplotlib`
- `seaborn`

## 🧼 Key Steps

1. **Load and inspect** the dataset  
   Check shape, data types, and basic statistics

2. **Analyze missing values**  
   - Visualize missing data
   - Drop rows with missing `name`

3. **Handle invalid data**  
   - Remove listings with price ≤ 0

4. **Remove outliers**  
   - Apply **Interquartile Range (IQR)** method for key numerical columns

5. **Visualize data**  
   - Use boxplots to understand spread and detect extreme values

## 📊 Features Explored

- `price`
- `minimum_nights`
- `reviews_per_month`
- `availability_365`
- `number_of_reviews`
- `calculated_host_listings_count`

## 📈 Sample Output

The notebook includes visualizations like:

- Boxplots for key numerical features
- Missing value summaries
