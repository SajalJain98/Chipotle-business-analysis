# Chipotle Business Analysis

## Project Overview
This project analyzes Chipotle’s order dataset to extract actionable business insights.  
The goal was to apply data cleaning, exploratory data analysis (EDA), and visualization techniques to answer key business questions related to revenue, customer engagement, and menu performance.

The analysis was performed using Python, Pandas, Numpy, Seaborn, and Matplotlib.

---

## Objectives
- Clean and preprocess raw Chipotle order data for analysis.  
- Identify top-selling items and key revenue drivers.  
- Analyze order patterns and pricing distribution.  
- Simulate user activity to calculate Daily Active Users (DAU) and Weekly Active Users (WAU).  
- Provide business recommendations for menu strategy and customer retention.  

---

## Methodology
1. **Data Cleaning and Preparation**  
   - Removed currency symbols and converted prices to numeric values.  
   - Expanded multiple-quantity orders into separate rows.  
   - Handled missing values in choice descriptions.  
   - Simulated user IDs and activity dates to enable engagement analysis.  

2. **Exploratory Data Analysis (EDA)**  
   - Calculated total revenue and average order value (AOV).  
   - Identified the top items by sales volume and revenue.  
   - Conducted basket analysis to evaluate common item pairings.  
   - Visualized pricing distribution to identify trends and outliers.  

3. **Customer Engagement Analysis**  
   - Calculated DAU and WAU metrics.  
   - Compared engagement patterns across time windows.  

4. **Menu Performance and Strategy**  
   - Highlighted high-frequency and high-revenue items.  
   - Suggested bundling strategies based on common item pairs.  

---

## Key Insights
- Burritos and bowls are the most popular and revenue-driving items.  
- Average order value reveals opportunities for upselling sides such as chips and guacamole.  
- DAU fluctuates while WAU remains stable, suggesting weekly return behavior rather than daily.  
- Basket analysis shows potential for combo meal promotions.  

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/SajalJain98/Chipotle-business-analysis.git
   cd Chipotle-business-analysis
  
