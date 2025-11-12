# Sales-Profit-Insights-Dashboard---Power-BI-Project
The Sales &amp; Profit Insights Dashboard is an interactive Power BI project built to analyze and visualize key business performance metrics from the Sample Superstore dataset (2014–2017).
This dashboard provides insights into sales, profit, and profit margins across various categories, regions, and time periods, helping stakeholders make informed business decisions.

#Objectives

To design an interactive and dynamic dashboard for business analysis.
To track Total Sales, Total Profit, and Profit Margin % using KPI visuals.
To explore sales performance by Category, Region, and Month.
To demonstrate data cleaning, DAX, and visualization skills in Power BI.

#Tools & Technologies

Power BI Desktop — for data modeling and visualization
DAX (Data Analysis Expressions) — for calculated measures and KPIs
Power Query Editor — for data transformation and cleaning
Sample Superstore Dataset — for analysis

#Data Model & Transformations

The dataset was cleaned and transformed using Power Query:
Removed unnecessary blank rows and columns
Renamed inconsistent column headers
Converted date fields into correct format
Created custom DAX measures:
Total Sales = SUM('Sample - Superstore'[Sales])
Total Profit = SUM('Sample - Superstore'[Profit])
Profit Margin % = DIVIDE(SUM('Sample - Superstore'[Profit]), SUM('Sample - Superstore'[Sales]))


#Key Insights

🖥️ Technology category recorded the highest total sales.
🌍 West region achieved the highest profit margin.
📅 Sales showed consistent upward trend in 2017.
📊 Profit margins varied significantly by segment and region, offering scope for optimization

#Design Highlights

Clean, minimal layout with consistent color palette (Blue, White, Gray).
Professional typography: Segoe UI / DIN fonts.
Balanced placement of visuals with shadows and borders for clarity.
Interactive slicers enhance user exploration and insights.

#Learnings

Hands-on experience in Power BI dashboard creation.
Improved understanding of data cleaning, DAX formulas, and storytelling with data.
Practiced visual hierarchy and color balance for professional presentation.

