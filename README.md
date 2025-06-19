# Customer Segmentation Project
# Insights Report

## Introduction
This report summarizes the key insights derived from the customer segmentation analysis conducted on the Mall Customers dataset. The primary objective was to segment customers into distinct groups based on their age, annual income, and spending score using K-Means clustering, and to provide actionable marketing strategies for each identified segment.

## Data Collection and Cleaning
### Steps Taken:
1. *Loading the Dataset*: The dataset was loaded successfully and inspected for initial understanding.
2. *Missing Values*: No missing values were found in the dataset.
3. *Encoding Categorical Variables*: The Genre column, representing gender, was encoded as numerical values (Male: 1, Female: 0).
4. *Saving the Cleaned Dataset*: The cleaned dataset was saved as cleaned_mall_customers.csv.

## Exploratory Data Analysis (EDA)
### Descriptive Statistics:
- *Age*: Mean = 38.85, Std = 13.97
- *Annual Income*: Mean = 60.56k$, Std = 26.26k$
- *Spending Score*: Mean = 50.20, Std = 25.82

### Visualizations:
1. *Age Distribution*: Showed a wide age range from 18 to 70, with most customers clustered between 30 and 50.
2. *Annual Income Distribution*: Displayed a broad income range, with peaks around $20k and $80k.
3. *Spending Score Distribution*: Indicated a relatively even distribution across all scores from 1 to 99.
4. *Scatter Plot*: Displayed the relationship between annual income and spending score, revealing certain patterns influenced by gender.

## Customer Segmentation
### Methodology:
1. *Standardizing the Features*: Age, Annual Income, and Spending Score were standardized for clustering.
2. *K-Means Clustering*: Applied with 5 clusters.

### Cluster Insights:
#### Cluster 0: Young Low-Income High-Spenders
- *Characteristics*: Young individuals, lower annual incomes, high spending scores.
- *Marketing Strategy*: Focus on trendy, budget-friendly products. Offer discounts and loyalty rewards to sustain their high spending.

#### Cluster 1: Middle-Aged Average-Income Low-Spenders
- *Characteristics*: Middle-aged, average annual incomes, low spending scores.
- *Marketing Strategy*: Boost engagement through personalized marketing and incentives. Address barriers to spending with targeted promotions.

#### Cluster 2: High-Income High-Spenders
- *Characteristics*: High annual incomes, high spending scores.
- *Marketing Strategy*: Offer premium products and exclusive services. Provide personalized experiences and superior customer service.

#### Cluster 3: Low-Income Low-Spenders
- *Characteristics*: Low annual incomes, low spending scores.
- *Marketing Strategy*: Highlight budget-friendly options and value deals. Emphasize cost savings and essential benefits.

#### Cluster 4: Older High-Income Average-Spenders
- *Characteristics*: Older individuals, high annual incomes, average spending scores.
- *Marketing Strategy*: Focus on high-quality, reliable products. Use promotions that appeal to their purchasing power and preferences.

## Recommendations
### Personalized Marketing:
Tailor marketing messages to the specific needs and preferences of each customer segment to enhance engagement and spending.

### Loyalty Programs:
Implement or enhance loyalty programs to reward high spenders and encourage repeat purchases among low spenders.

### Product Differentiation:
Offer a diverse range of products that cater to the varying income levels and spending behaviors of each segment.

### Customer Feedback:
Regularly gather and analyze customer feedback to understand changing needs and adapt marketing strategies accordingly.

## Conclusion
The customer segmentation analysis has provided valuable insights into the distinct groups within the customer base. By implementing the recommended strategies, the company can effectively target each segment, optimize marketing efforts, and ultimately improve customer satisfaction and revenue.
 
