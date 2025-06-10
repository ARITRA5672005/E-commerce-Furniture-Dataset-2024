# E-commerce Furniture Dataset 2024 Project

## Introduction
This project explores the E-commerce Furniture Dataset 2024, aiming to analyze sales, trends, and customer preferences in the online furniture market. The dataset provides valuable insights into product performance and business strategies.

## Overview
The project involves data cleaning, exploratory data analysis, and visualization to uncover patterns in furniture sales. Key metrics such as revenue, top-selling products, and customer demographics are examined to support data-driven decision-making.  
Additionally, the project investigates seasonal trends and regional sales differences, offering a holistic view of the market landscape.

## Tools Used
- **Python**: Primary programming language for data analysis.
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive analysis and reporting.
- **Scikit-learn**: Applied for basic predictive modeling and clustering.
- **Excel**: Used for initial data inspection and quick summaries.

## Analysis
The exploratory data analysis was conducted in the [`2_Exploratory_Data_Analysis.ipynb`](Project/2_Exploratory_Data_Analysis.ipynb) notebook. This analysis includes:

- Data cleaning and preprocessing steps.
- Examination of sales distribution across product categories.
- Identification of top-performing products and regions.
- Visualization of seasonal and regional sales trends.
- Insights into customer demographics and purchasing behavior.

### Results

#### Distribution of Units Sold
![Distribution of Units Sold](Project/Images/Distribution%20of%20Units%20Sold.png)

The above visualization illustrates the distribution of units sold across different product categories. Key insights include:
- **High concentration** of sales in a few popular categories, indicating strong customer preferences.
- **Long tail** of less frequently sold items, suggesting opportunities for niche marketing.
- **Potential outliers** in certain categories, which may warrant further investigation into promotional effectiveness or data quality.
- The distribution helps identify which products drive the majority of revenue and where inventory or marketing strategies can be optimized.

#### Price vs Units Sold
![Price vs Units Sold](Project/Images/Price%20vs%20Units%20Sold.png)

This visualization examines the relationship between product price and the number of units sold. Key insights include:
- **Negative correlation**: Lower-priced items tend to have higher sales volumes, indicating price sensitivity among customers.
- **Premium segment**: Some higher-priced products still achieve notable sales, suggesting a market for premium offerings.
- **Outliers**: A few products deviate from the general trend, which may be due to unique features, brand reputation, or targeted promotions.
- Understanding this relationship helps optimize pricing strategies and identify opportunities for both value and premium product lines.

#### Units Sold by Price Range
![Units Sold by Price Range](Project/Images/Units%20Sold%20by%20Price%20Range.png)

This visualization breaks down the number of units sold within different price ranges. Key insights include:
- **Majority of sales** occur in the lower to mid-price ranges, reinforcing the price sensitivity observed in earlier analyses.
- **Higher price ranges** contribute fewer unit sales but may still drive significant revenue due to higher margins.
- **Distinct peaks** in certain price brackets suggest popular price points that attract more customers.
- **Opportunities** exist to optimize product offerings and marketing strategies around the most active price ranges, while also exploring ways to boost sales in higher price segments.

#### Units Sold by Shipping Type
![Units Sold by Shipping Type](Project/Images/Units%20Sold%20by%20Shipping%20Type.png)

This visualization shows how units sold are distributed across different shipping types. Key insights include:
- **Standard shipping** accounts for the majority of sales, indicating customer preference for cost-effective delivery options.
- **Express and premium shipping** types, while less common, may attract customers seeking faster delivery, often for higher-value purchases.
- **Free shipping promotions** can significantly boost sales volume, suggesting an effective marketing lever.
- Understanding shipping preferences helps optimize logistics, improve customer satisfaction, and tailor promotional strategies.

## What I Learned
- Enhanced skills in data wrangling and visualization.
- Gained experience in interpreting e-commerce datasets.
- Improved ability to extract actionable insights from complex data.
- Developed better strategies for handling real-world data challenges.
## Challenges
- Handling missing or inconsistent data entries.
- Managing large dataset size and optimizing performance.
- Interpreting ambiguous or incomplete product information.
- Addressing data imbalance in certain product categories.
- Ensuring visualizations effectively communicate findings to stakeholders.

## Conclusion
The project provided a comprehensive understanding of the e-commerce furniture market. The analysis highlighted key trends and customer behaviors, offering valuable guidance for business strategies and future research.  
Future work could involve deeper predictive analytics, integration with external datasets, and the development of interactive dashboards for real-time insights.