# Customer Segmentation Analysis

## Overview
This project analyzes customer transaction data to identify the most profitable customers and the bestselling products. The analysis leverages **K-Means clustering** to segment customers based on their spending habits and purchase frequency, helping the marketing team focus on the most valuable customer groups. Additionally, the project identifies top-selling products to optimize marketing efforts.

### Key Findings:
- Identified the **top 3 most profitable products** based on total sales.
- Performed **customer segmentation** to identify the most loyal and profitable customers using **K-Means clustering**.
- Analyzed customer characteristics to help the marketing team target the right audience with personalized strategies.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/repository-name.git
Navigate to the project directory:
cd repository-name


Usage
Run the Jupyter Notebook or Python script:

If using Jupyter Notebook, open the .ipynb file and run the cells:
jupyter notebook

If running the Python script directly, execute it from the terminal:
python script_name.py


Input:
The dataset (merged_data.csv) should be placed in the project directory.
The script will load and preprocess the data, calculating total sales and purchase frequency for each customer.

Output:
The results will be saved in the customer_segments.csv file.
The clusters will be visualized to show the customer segments.


Results
Top 3 Profitable Products: These products were identified based on total sales across all transactions:

Product A: High sales volume with significant revenue contribution.
Product B: A best-seller that brings in steady profits.
Product C: Although not as popular as Products A and B, it contributes significantly to revenue.
Loyal Customer Segments:

K-Means clustering was applied to segment customers based on their total sales and purchase frequency.
The customers were divided into 3 clusters:
Cluster 1: High-spending and frequent customers, who are the most loyal and profitable.
Cluster 2: Moderate spenders with medium purchase frequency.
Cluster 3: Low-spending and occasional buyers, likely the least loyal customers.
The KMeans model helps identify which customer groups are more valuable, allowing the marketing team to focus on high-value segments.

Requirements:
Python 3.x
pandas
numpy
sklearn
matplotlib
seaborn

To install these dependencies, you can use pip:


Conclusion
This project provides valuable insights into customer behavior by analyzing transaction data to identify profitable products and customer segments. By leveraging K-Means clustering, we were able to segment customers into three distinct groups based on their spending habits and purchase frequency. These segments represent different levels of loyalty and profitability, allowing the marketing team to target high-value customers with tailored campaigns.

Key Outcomes:
Top 3 Profitable Products: The analysis helped identify the most profitable products, which can now be emphasized in marketing and sales strategies to boost revenue further.
Customer Segmentation with K-Means: By dividing customers into distinct clusters, we identified which groups are more likely to be loyal, frequent buyers and which ones may need more attention to boost their engagement.
Strategic Focus for Marketing: The findings from the customer segments provide a roadmap for marketing efforts, where resources can be focused on engaging the high-value segments, optimizing product promotions, and increasing sales.
In conclusion, the combination of transaction analysis and machine learning helps businesses make data-driven decisions. It empowers marketing teams to focus their efforts on the most profitable customers and products, ultimately improving customer retention, product sales, and overall business performance.



