# OmniMart Retail Challenge: Optimizing Customer Experience and Sales



## Project Overview
This project is part of the **Challenge 1: TMP OmniMart Retailers** initiative. As a multinational retail company, OmniMart aims to leverage its vast database of customer transactions and feedback to gain deeper insights into customer behavior, improve sales, increase retention, and optimize marketing strategies. Our team conducted a comprehensive Exploratory Data Analysis (EDA) on the provided retail dataset to uncover actionable insights and identify growth opportunities.

### Team: Code Warriors
- **Team Members**:
  - Sudip Madhu
  - Manobendra Ghosh
  - Ankit Ghosh
  - Sayan Hassan

## Brief Problem Statement
OmniMart Retailers, a multinational company, possesses a vast database of customer transactions and feedback. The goal is to perform a comprehensive Exploratory Data Analysis (EDA) to uncover actionable insights, focusing on key business questions and identifying opportunities for growth. The mission includes:

1. **Analyze Customer Behavior**: Identify distinct customer segments based on purchasing habits, demographics, and income. Determine average spend per customer and analyze spending variations across segments (e.g., age, gender, location). Uncover trends in customer loyalty by examining purchase frequency and total purchases.

2. **Evaluate Product Performance**: Identify the most and least popular product categories and brands. Analyze relationships between product feedback (ratings) and sales performance. Investigate if certain product types are more popular with specific customer segments.

3. **Optimize Operations and Logistics**: Analyze the impact of different shipping methods on customer order status (e.g., delivered vs. canceled). Examine common payment methods and their correlation with order value.

4. **Actionable Insights & Recommendations**: Based on findings, prepare a detailed report or presentation outlining key insights and providing clear, data-driven recommendations to the OmniMart leadership team. These insights can be used to create targeted marketing campaigns, improve the product catalog, or enhance the overall customer experience.

Our approach involved loading the dataset (`retail_data.csv`), performing data cleaning (handling missing values, duplicates, and inconsistencies), conducting statistical analysis and visualizations using libraries like Pandas, NumPy, Seaborn, and Matplotlib, and deriving insights to drive business decisions.

## Summary of Findings
Here is a bullet-point summary of our most significant insights from the EDA:

### Customer Behavior
- **Demand Trends**: Popular products (identified via value counts) highlight strong demand in certain categories, such as electronics and clothing, indicating opportunities for targeted promotions.
- **Spending Patterns**: The spending distribution reveals that most customers are mid-range buyers, with a smaller segment of high-spenders contributing significantly to revenue.
- **Loyalty Indicators**: A notable repeat purchase rate suggests a potential loyal customer base, which could be nurtured through personalized loyalty programs.

### Operations & Logistics
- **Shipping Preferences**: Certain shipping methods (e.g., Standard) are used far more frequently than others, suggesting a need to optimize logistics and resources around these popular options.
- **Payment Trends**: Preferences for methods like Credit Card or Cash on Delivery (COD) inform better transaction system planning and could reduce friction in the checkout process.
- **Cancellation Correlations**: Order cancellations appear linked to specific shipping methods and payment choices, pointing to potential pain points in the fulfillment process.

These insights were derived from key analyses in our Jupyter Notebook (`Code_Warriors_Challenge1.ipynb`), including value counts, distribution plots, correlation matrices, and cross-tabulations.

## Recommendations
Based on our findings, we propose the following data-driven actions:
1. **Inventory Optimization**: Prioritize stocking popular items from high-demand categories to minimize stockouts and maximize sales.
2. **Customer Retention Strategies**: Implement loyalty offers and personalized marketing for repeat customers to boost retention and lifetime value.
3. **Logistics Efficiency**: Invest in improving the most-used shipping methods (e.g., faster processing for Standard shipping) to reduce delays and enhance customer satisfaction.
4. **Cancellation Reduction**: Conduct deeper investigations into high-cancellation combinations (e.g., certain shipping + payment methods) and address underlying issues, such as better communication or alternative options.

## Project Structure
- **Code_Warriors_Challenge1.ipynb**: The main Jupyter Notebook containing data loading, cleaning, EDA, visualizations, and insights.
- **retail_data.csv**: The dataset used for analysis (zipped in `retail_data.zip` if applicable).
- **README.md**: This file – your quick guide to the project.
- **Project Briefing.pdf**: The original problem statement document.

## Getting Started
### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib` (install via `pip install -r requirements.txt` if provided).

### Installation & Running the Analysis
1. Clone the repository:
   ```
   git clone https://github.com/manhattanproject-ai/Challenge1_TMP_OmniMart-Retailers.git
   ```
2. Navigate to the project directory:
   ```
   cd Challenge1_TMP_OmniMart-Retailers
   ```
3. Install dependencies:
   ```
   pip install pandas numpy seaborn matplotlib
   ```
4. Run the Jupyter Notebook:
   ```
   jupyter notebook Code_Warriors_Challenge1.ipynb
   ```

## Visualizations & Key Outputs
In the notebook, you'll find:
- Histograms for spending distribution.
- Bar charts for popular products and categories.
- Heatmaps for correlations between variables (e.g., shipping method and order status).
- Pie charts for payment method preferences.

These visuals provide a clear, intuitive understanding of the data trends.


## Acknowledgments
- Thanks to OmniMart for providing the dataset and challenge.
- Built with open-source tools like Jupyter and Pandas for efficient data analysis.

For questions or collaborations, contact the team at smadhu.882005@gmail.com . Let's optimize retail together! 🚀
