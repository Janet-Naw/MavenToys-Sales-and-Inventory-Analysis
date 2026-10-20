# Sales Performance and Inventory Analysis
**Tools:** Excel | Power BI
**Dataset:** Mexico Toy Sales and Inventory Dataset (Maven Analytics) — 800K+ transactions

## Project Overview
Analyzed 800K+ sales transactions across 50 stores in Mexico and 35 products to track monthly sales trend, product performance and inventory status. 

## Business Questions Answered
- Which product categories drive the biggest profits? Is this the same across store
  locations?
- Are there any seasonal trends or patterns in the sales data?
- How much money is tied up in inventory at the toy stores? How long will it last? 

## What I Did And Challenges 
- Cleaned and formatted data in Excel.
- Sales table contained no monetary values — only units sold. Applied INDEX/MATCH to extract
  unit price and unit gross profit from the product table, then calculated sales amount and
  gross profit per transaction directly in Excel before loading into Power BI.
- Built an interactive Power BI dashboard for sales performance and inventory status with
  dynamic filters by year and product category.
- Year 2 data covers January–September only, excluding Q4. For a fair YoY comparison,
  compared sales for January–September across both years. Year 2 sales were higher, with
  potential for further growth if the typical Q4 sales peak continues.
- Note: YoY% shown as blank where no prior year data exists — to distinguish from 0% change

## Key Findings
- Over the two years, Toys product category drove the most profit.
- Electronic profit dropped by almost half in 2023, despite being the highest in 2022. Need
  to look into why its demand dropped.
- Arts and Crafts profit rose significantly in 2023.
- Sales follow a seasonal pattern: lowest in January, February and August, and highest at
  year-end in 2022 (November and December).
- Sales grew about 30% in 2023, when compared January to September in both years.
- Most categories fluctuate only mildly, but Electronics is strong early in the year and
  weak toward the end, while Art & Crafts shows the opposite pattern.
- Downtown stores generate the most sales (about 57% of total), and Toys is their highest
  category.
- In commercial area, Electronic is the top category.
- Airport stores generate the least, at around 9% of sales.
- Worth prioritising restocking products that are out of stocks in many stores. Playfoam
  (under Art & Crafts) is out of stock in 13 stores.
- In terms of stores, worth prioritising based on their daily average sales.
- Worth reviewing cost of good sold and product price, since current profit margin is under
  30%. 

## Dashboard Preview
<img width="2797" height="1819" alt="Toy_Sales_Performance_Analysis_1" src="https://github.com/user-attachments/assets/13c1dfde-0711-485e-a4c3-25cd5bb8a776" />

<img width="2794" height="1809" alt="Toy_Sales_Performance_Analysis_2" src="https://github.com/user-attachments/assets/28bf47fd-87e8-4df4-9eaa-c556d97a38cd" />

<img width="2800" height="1809" alt="Toy_Inventory_Status_Analysis" src="https://github.com/user-attachments/assets/3689045e-7051-499c-97a1-fb42bc1e760e" />

## Files in this Repository
- Toy_Sales_Performance_Analysis1.png (Sales Dashboard Screenshot for quick view)
- Toy_Sales_Performance_Analysis2.png (2023 Sales Dashboard Screenshot for quick view)
- Toy_Inventory_Status_Analysis.png (Inventory Dashboard for quick view)
- Toy_Sales_Key_Insights.png (Insights for quick view)
- Data_Model_View.png (Power BI data model view)
- Maven_Toys_Sales_And_Inventory_Analysis_ByJanet.pbix (Power BI file — download and open in
  Power BI Desktop to explore full dashboard, measures and data model interactively)
  
## Data Source
Maven Analytics — Mexico Toy Sales and Inventory Dataset
https://mavenanalytics.io/data-playground/mexico-toy-sales 
