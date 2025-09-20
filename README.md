👕 Men’s T-Shirt Sales Analytics Dashboard
📝 Problem Statement

The men’s apparel market is highly competitive, with numerous brands offering a wide range of t-shirts. To make informed business decisions, companies need insights into discounts, profits, product variety, and pricing strategies.

This project focuses on analyzing men’s t-shirt sales data to identify the top and bottom performing brands based on various business KPIs.

By leveraging Azure (for data storage), SQL (for data cleaning & transformation), and Power BI (for visualization), we can answer questions such as:

Which brands offer the highest discounts?

Which brands generate the best profit margins?

Which brands dominate in variety and product range?

Which brands lead in pricing strategy?

⚙️ Steps Followed

Step 1: Data ingestion into Azure and setup for structured storage.

Step 2: Data cleaning & transformation using SQL (handling duplicates, null values, formatting, and preparing fact/dimension tables).

Step 3: Imported cleaned dataset into Power BI Desktop.

Step 4: Created calculated measures for:

Average Discount %

Average Profit %

Average Sales Price

Number of Varieties per Brand

Step 5: Built Top 5 / Bottom 5 brand comparisons using DAX and filters.

Step 6: Added slicers to analyze data by category, time, or other business attributes (if available).

Step 7: Applied professional themes and formatting for clear storytelling.

Step 8: Published the report to Power BI Service for interactive use.

📸 Snapshots of Dashboard
Top 5 Brands by Average Discount %
<img width="595" height="291" alt="Image" src="https://github.com/user-attachments/assets/d96a8e52-55d4-48e4-9231-052e63b27b5a" />

Top 5 Brands by Highest Average Profit %
<img width="595" height="291" alt="Image" src="https://github.com/user-attachments/assets/d96a8e52-55d4-48e4-9231-052e63b27b5a" />

Top 5 Brands by Number of Varieties

Top 5 Brands by Average Sales Price

Bottom 5 Brands by Average Profit %

(Replace these links with actual screenshot paths or GitHub-uploaded image URLs)

🔍 Insights

From the analysis, the following insights can be drawn:

1️⃣ Discount Strategy – Top brands offering higher discounts may attract more customers but could risk lowering profit margins.

2️⃣ Profitability – Brands with consistently high average profit % indicate effective pricing and cost management.

3️⃣ Variety Leadership – Brands with more t-shirt varieties dominate shelf presence and appeal to diverse customer preferences.

4️⃣ Sales Price Trends – Higher pricing strategies may indicate premium positioning of brands.

5️⃣ Weak Performers – Bottom 5 brands by profit % highlight opportunities for optimization in pricing or cost control.

🛠️ Tools & Technologies

Azure → Cloud-based data storage.

SQL → Data cleaning, transformation, and analysis.

Power BI → Data modeling, dashboard building, and visualization.

🚀 How to Run This Project

Clone this repository:

git clone https://github.com/<username>/mens-tshirt-analytics.git
cd mens-tshirt-analytics


Upload dataset to Azure SQL Database.

Run provided SQL scripts for data cleaning & transformation.

Open Power BI file (.pbix) → connect it to your Azure SQL instance.

Explore the dashboards interactively or publish to Power BI Service.

📌 Conclusion

This project provides a clear view of how different men’s t-shirt brands perform across discounts, profitability, product variety, and pricing. These insights can help businesses fine-tune their marketing strategies, pricing models, and product diversification plans to stay ahead in the competitive apparel market.

✨ Created with Azure | SQL | Power BI
