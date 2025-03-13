# eda_analysis_on_nyc_Airbnb
# NYC Airbnb Data Analysis

Overview
This project conducts an Exploratory Data Analysis (EDA) on the NYC Airbnb dataset to uncover patterns and insights. The analysis includes data cleaning, univariate, bivariate, and multivariate analysis, along with various visualizations.

Dataset
- *File*: AB_NYC_2019.csv
- *Source*: New York City Airbnb listings for 2019

Prerequisites
Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

 Project Structure
1. *Data Cleaning*: Handle missing values, remove duplicates, standardize data, and treat outliers.
2. *Univariate Analysis*: Summary statistics, frequency distributions, histograms, box plots, and violin plots.
3. *Bivariate Analysis*: Scatter plots and correlation heatmaps.
4. *Multivariate Analysis*: Pair plots and heatmaps.

Step-by-Step Execution

 Step 1: Data Cleaning
- Handle missing values in name, host_name, reviews_per_month, and last_review.
- Remove duplicate records.
- Standardize categorical values.
- Treat outliers in price and minimum_nights using the IQR method.
- Drop irrelevant columns like id, host_id, and last_review.

 Step 2: Univariate Analysis
- Summary statistics (describe(), value_counts()).
- Frequency distribution for categorical variables.
- Histograms for numerical features.
- Box plots and violin plots for visual analysis.

Step 3: Bivariate Analysis
- Scatter plots for price against minimum_nights, number_of_reviews, and reviews_per_month.
- Correlation heatmap to identify relationships between numerical variables.

Step 4: Multivariate Analysis
- Pair plot to explore multiple variable relationships simultaneously.

Output Files
- histograms_nyc.png
- scatter_plots_nyc.png
- heatmap_nyc.png
- boxplot_price_neighbourhood.png
- violinplot_price_room_type.png
- pairplot_nyc.png


Conclusion
This project successfully analyzes the NYC Airbnb dataset, providing valuable insights through data cleaning, visualization, and statistical analysis.
