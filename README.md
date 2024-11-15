# Instacart-Customer-Behavior-Analysis
# Customer Behavior Analysis Project

## Project Overview
This project analyzes customer purchase behavior using the **Instacart Market Basket Analysis dataset**. The goal is to extract actionable insights through customer segmentation, product preferences, and shopping patterns. The analysis uses techniques such as clustering, exploratory data analysis (EDA), and lifetime value (CLV) estimation to help businesses design data-driven marketing strategies.

---

## Dataset
### Source
The dataset is from the [Instacart Market Basket Analysis](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data) competition on Kaggle.

### Files Included
- **aisles.csv**: Contains data on different product aisles.
- **departments.csv**: Details about product departments.
- **order_products__prior.csv**: Information on products in prior orders.
- **order_products__train.csv**: Training dataset for products in orders.
- **orders.csv**: Includes order details like user ID, order timing, and sequence.
- **products.csv**: Contains product details, including product name and department IDs.

---

## Key Objectives
1. **Customer Segmentation**:
   - Use clustering techniques to group customers based on purchasing behavior.
   - Identify and interpret unique characteristics of each customer segment.

2. **Product Insights**:
   - Analyze top products purchased by different customer segments.
   - Evaluate reorder ratios and purchase frequency to understand product loyalty.

3. **Shopping Behavior Analysis**:
   - Explore purchase patterns by time of day and day of the week.
   - Identify peak shopping hours and days to optimize marketing strategies.

4. **Customer Lifetime Value (CLV)**:
   - Estimate CLV for each customer segment to prioritize high-value groups.

---

## Methods and Techniques
1. **Exploratory Data Analysis (EDA)**:
   - Visualized trends in customer shopping behavior.
   - Identified popular aisles, departments, and products.

2. **Clustering Analysis**:
   - Performed K-Means clustering to segment customers into meaningful groups.
   - Validated clusters using the elbow method and silhouette scores.

3. **Customer Lifetime Value (CLV) Calculation**:
   - Used purchase frequency and average order size to estimate CLV for each segment.

4. **Behavioral Analysis**:
   - Analyzed purchase timing trends to identify peak shopping hours and days.
   - Examined product-specific trends (e.g., eggs and universal appeal).

---

## Key Insights
1. **Customer Segments**:
   - High-frequency shoppers prioritize fresh produce like bananas and organic items.
   - Occasional and bulk shoppers exhibit distinct shopping patterns.

2. **Product Preferences**:
   - Top products include bananas, strawberries, and organic avocados.
   - Universally appealing items, like eggs, have high reorder rates but do not dominate specific clusters.

3. **Shopping Patterns**:
   - Most orders occur between **10 AM and 3 PM** on weekends.
   - Promotions and campaigns are most effective on Sundays and Mondays.

4. **Customer Lifetime Value**:
   - High-CLV clusters contribute significantly to overall revenue, requiring loyalty and retention strategies.
   - Low-CLV clusters represent opportunities for re-engagement campaigns.

---

## Tools and Libraries Used
- **Python**:
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `mlxtend`
- **Jupyter Notebook**: For organizing and visualizing the analysis.

---

## Business Applications
1. **Marketing Campaigns**:
   - Design targeted campaigns for high-value customers (e.g., exclusive discounts and loyalty rewards).
   - Re-engage low-value clusters with personalized offers and reminders.

2. **Inventory Management**:
   - Optimize inventory for high-demand products like fresh produce and organic items.
   - Align stock levels with peak shopping hours and days.

3. **Promotional Strategies**:
   - Schedule sales and promotions during peak shopping periods (late mornings and weekends).
   - Highlight universally popular products like eggs in broader campaigns.

---

## How to Run the Project
1. Download the dataset from [Kaggle](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data).
2. Place all `.csv` files in the `data/` folder within the project directory.
3. Open the Jupyter Notebook `Customer-Behaviour-Analysis.ipynb` and run each cell sequentially.
4. Review the outputs, visualizations, and interpretations provided in the notebook.

---

## Future Work
- Analyze seasonal trends in customer shopping behavior.
- Incorporate customer demographics for deeper segmentation.
- Implement advanced clustering techniques (e.g., DBSCAN, hierarchical clustering).

---

## Acknowledgments
- Dataset provided by [Kaggle](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data).
- Thanks to Instacart for sharing anonymized customer data for research purposes.
