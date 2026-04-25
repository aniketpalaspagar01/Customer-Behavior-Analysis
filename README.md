🛒 Customer Shopping Behaviour Analysis

📌 Project Overview
This project analyses customer shopping behaviour using transactional data from 3,900 purchases across various product categories. The primary objective is to uncover actionable insights into spending patterns, customer segments, product preferences, and subscription behaviour to guide strategic business decisions.
🛠️ Tech Stack & Tools

Python (Pandas): For data loading, manipulation, and Exploratory Data Analysis (EDA).

PostgreSQL: For executing complex queries on cleaned data to extract business transactions and insights.

Power BI: To build dynamic and interactive dashboards for data visualization.

Gamma: To create a professional presentation summarizing strategic recommendations.

🚀 Step-by-Step Analytical ProcessStep 
1: Data Preparation & EDA (Python)
Data Loading: Imported the raw dataset containing 18 columns and 3,900 rows using pandas.

Missing Data Handling: Identified 37 missing values in the Review Rating column and imputed them using the median rating of their respective product categories.

Feature Engineering: Created new features such as age_group (by binning customer ages) and purchase_frequency_days to enable deeper analysis.

Standardization: Renamed columns to snake_case for better readability and removed redundant fields like promo_code_used.

Step 2: Database Integration & SQL Analysis (PostgreSQL)
Connected the Python script directly to PostgreSQL to load the cleaned DataFrame.

Executed structured queries to answer key business questions, such as comparing revenue by gender, identifying high-spending discount users, and calculating total revenue contribution across different age groups.

Step 3: Data Visualization (Power BI)Designed a comprehensive "Customer Behavior Dashboard".

Visualized key metrics including Average Purchase Amount ($59.76), Average Review Rating (3.75), Sales by Category, and Revenue by Age Group to make the data easily digestible for stakeholders.

Step 4: Insights & Presentation (Gamma)

Compiled the findings into a high-quality presentation using Gamma.

Translated raw numbers into strategic business recommendations focused on driving revenue and customer loyalty.

📊 Key Business Insights

Demographic Revenue Engine: Young adults (ages 18-35) are the primary revenue drivers, generating 51.5% of total sales through frequent repeat purchases. Male customers generated $73,500, representing 67.6% of the total revenue.

Customer Segmentation: The vast majority of the customer base belongs to the "Loyal" segment, comprising 2,721 repeat buyers.

Product Performance: "Gloves" is the highest-rated product with an average rating of 3.86. Conversely, some products like "Hats" are highly discount-dependent, with 50% of purchases involving a discount.

💡 Strategic Recommendations

1 Boost Subscriptions: Promote exclusive benefits tailored specifically for subscribers to increase recurring revenue.
2 Targeted Marketing: Focus marketing efforts on the high-revenue young adult demographic and express-shipping users.
3 Review Discount Policy: Balance short-term sales boosts with long-term margin control, especially for discount-dependent items like hats and sneakers.
4 Customer Loyalty Programs: Implement structured rewards for repeat buyers to transition more customers into the highly profitable "Loyal" segment.
