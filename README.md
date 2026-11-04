# Retail Sales Dashboard (Excel)

An Excel dashboard that analyses 1,000 retail transactions to show what drives sales across product categories, customer groups, price points and time.

## Business Question
Which products, customers and periods generate the most revenue, and where should the business focus?

## Dataset
- 1,000 transactions, 10 columns, 1 Jan 2023 to 1 Jan 2024
- Fields: transaction ID, date, customer ID, gender, age, product category, quantity, price per unit, total amount
- Currency is not stated, so values are shown without a symbol

## Tools and Skills
Microsoft Excel: SUMIFS, COUNTIFS, AVERAGEIFS, SUMPRODUCT, data validation dropdowns, charts, dashboard design

## Data Checks
- No missing values or duplicate transaction IDs
- Quantity x Price per Unit equals Total Amount for every row
- Every customer ID appears once, so repeat-purchase analysis is not possible
- Only 2 transactions fall in January 2024, so trend charts use 2023

## Dashboard
- **KPIs:** Total Revenue, Transactions, Units Sold, Average Order Value, Average Customer Age
- **Charts:** monthly revenue, revenue by category, revenue share by gender, average order value by age group, revenue by day of week, revenue by price point
- **Filters:** Category and Gender dropdowns update the KPIs and charts

## Key Findings
1. Items priced at 300 or 500 make up 39.6% of transactions but 88.4% of revenue
2. Categories are balanced: Electronics 34.4%, Clothing 34.1%, Beauty 31.5%
3. Average order value falls with age, from 500 (18-25) to 412 (56-64)
4. Q3 is the weakest quarter; September is the lowest month, May the highest
5. Saturday is the strongest day, Thursday the weakest
6. Female customers generate 51.1% of revenue, with almost identical order values to male customers

#DASHBOARD!<img width="735" height="432" alt="BETECHFIED SALES DASHBOARD" src="https://github.com/user-attachments/assets/31e12069-08e8-44f6-9ad2-1abaca41c7ef" />











#BARCHART!<img width="1263" height="428" alt="PRODUCT BY SALES" src="https://github.com/user-attachments/assets/f09ed95a-eb7a-4ecf-875b-9f9992005426" />



















#BARCHART!<img width="1238" height="430" alt="Screenshot 2026-11-04 110309" src="https://github.com/user-attachments/assets/a779d5f7-48e4-4d42-b54e-be0028430875" />











#PIECHART!<img width="575" height="440" alt="Screenshot 2026-11-04 110203" src="https://github.com/user-attachments/assets/6b1c3beb-319e-47f2-adba-2be8d129a1f4" />














#LINECHART!<img width="903" height="425" alt="Screenshot 2026-11-04 110239" src="https://github.com/user-attachments/assets/992ea292-060a-43f3-9a86-3b4c89767653" />







## Recommendations
1. Prioritise availability and promotion of premium items
2. Target premium campaigns at younger customers
3. Plan a promotion for Q3 and stock up for May and Q4
4. Focus staffing and campaigns on Saturdays; test a mid-week offer

## Limitations
- No cost, margin, stock or location data, so profit and regional analysis are not possible
- Each category has the same price spread, which suggests simulated data, so findings are descriptive

## Files
