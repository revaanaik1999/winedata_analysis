# Wine Data Analysis

This repository contains a Jupyter notebook that performs exploratory data analysis (EDA) on a dataset of wine characteristics. The primary focus of this analysis is to understand the
relationships between various features (such as residual sugar, alcohol content, etc.) and the wine's quality.

# Dataset

The dataset is obtained from Kaggle and the .CSV files are uploaded as well.

* Key Features in the Dataset:
  - Fixed Acidity: Acidity level of the wine
  - Volatile Acidity: Amount of acetic acid in the wine
  - Citric Acid: Helps maintain the wine’s freshness
  - Residual Sugar: Amount of sugar left after fermentation
  - Chlorides: Amount of salt in the wine
  - Free Sulfur Dioxide: Free form of SO2 in the wine
  - Total Sulfur Dioxide: Bound and free forms of SO2
  - Density: Density of the wine
  - pH: Acidity/alkalinity measurement
  - Alcohol: Alcohol content of the wine
  - Quality: Score of wine quality

# Analysis and Steps

* Data Preprocessing
  - Data Loading: The dataset is loaded into a Pandas DataFrame.
  - Data Cleaning: Handled missing or null values, checked for duplicates, and ensured the dataset is ready for analysis.
  - Data Wrangling: The necessary transformations were applied to optimize the data for visualization and analysis.
 
* Exploratory Data Analysis (EDA)
  - Correlation Analysis: Investigated correlations between variables using heatmaps to identify significant relationships.
  - Visualization: Generated visualizations to uncover insights:
    - Bar charts to explore the relationship between wine quality, residual sugar content, alcohol content, and more.
    - Histograms and line plots to study the distribution of features like alcohol levels.

# Tools and Libraries Used:
  - Pandas: For data manipulation and cleaning.
  - NumPy: For numerical computations.
  - Matplotlib: For plotting charts and graphs.
  - Seaborn: For advanced data visualizations.
