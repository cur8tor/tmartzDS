# Tutorial on Instacart Data Analysis

[Slide Presentation](https://github.com/cur8tor/tmartzDS/blob/6bd9bcdc5bcbfc64d154366d6c8e6c43c4bd81df/presentation.pdf)

[GitHub Page](https://cur8tor.github.io/tmartzDS/)

**Author: Tanner Martz**

**Tulane University**

**CMPS 3160 Intro. to Data Science**


## Project Overview
### Objective
The primary goal is to determine the most popular items ordered on Instacart and understand the factors influencing their popularity. This knowledge will then be used to predict the number of orders for new products.

### Approach
1. **Data Collection and Preparation**: 
   1. Instacart dataset - (https://www.kaggle.com/competitions/instacart-market-basket-analysis/data) 
   2. USDA Food Central Database for nutritional information - (https://fdc.nal.usda.gov/index.html)
2. **Exploratory Data Analysis (EDA)**: Analyzing reorder patterns, popular products, and their features.
3. **Feature Engineering**: Enhancing the dataset with nutritional data and other relevant attributes.
4. **Machine Learning Modeling**: Utilizing Random Forest and XGBoost regressors to predict product popularity based on various features.

### Insights
- **Key Factors**: Reorder history, product type (especially fruits and vegetables), and nutritional content (water and protein content) are crucial in determining a product's popularity.
- **Health Trend**: A positive correlation between the healthiness of products (high in water and protein) and their popularity.
- **Future Directions**: Expansion of the project to include additional data sources, feature engineering, different machine learning algorithms, and enhanced visualizations.

### Methodology and Code
- **Data Analysis**: Code snippets for data manipulation, visualization, and analysis using Pandas, Seaborn, and Matplotlib.
- **Machine Learning**: Code for model building, training, and evaluation, including feature importance analysis.

### Conclusions
The study reveals a strong influence of reorder rates, product categories, and nutritional values on product popularity on Instacart. This understanding can guide effective product placement strategies and inventory management for online grocery stores.

This tutorial serves as a comprehensive guide to understanding consumer behavior in online grocery shopping, particularly on Instacart, using data science techniques. The methodologies and insights presented here can be leveraged by data scientists and market analysts in similar contexts.


---