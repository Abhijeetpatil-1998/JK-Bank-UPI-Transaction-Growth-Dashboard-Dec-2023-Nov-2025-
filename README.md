# J&K Bank UPI Transaction Growth Dashboard (Dec 2023 – Nov 2025)

## Project Objective
The team wants a single report to track month-over-month (MoM) growth of J&K Bank's total UPI transactions (FT & NFT), so that management can see the growth trend, spot months with declines, and plan for the coming months.

## Dataset used
- Monthly UPI transaction totals (FT & NFT) for J&K Bank, December 2023 to November 2025
- Fields: Year, Month, Current Month value, Previous Month value, MoM Growth %

## Questions (KPIs)
1. What was the total transaction volume in the first and latest month, and what is the overall growth?
2. What is the MoM growth % for every month?
3. Which months had the highest and the lowest growth?
4. Which months showed a decline compared to the previous month?
5. How does 2025 compare with 2024?
6. What is the peak monthly volume so far?

## Dashboard Interaction
-<a href="https://github.com/Abhijeetpatil-1998/JK-Bank-UPI-Transaction-Growth-Dashboard-Dec-2023-Nov-2025-/blob/main/Client%20wise%20Monthly%20Growth%20%25%20(%20J%26K%20Bank).jpeg">View Dashboard</a>

## Process
1. Collected monthly transaction totals and checked for missing months and incorrect values.
2. Cleaned the data: consistent data types, month order and number formats.
3. Built the data model and created a measure for MoM Growth % = (Current M − Previous M) / Previous M.
4. Created visuals: a year/month table with up-down indicators and a column chart of MoM growth %.
5. Combined both visuals into one dashboard.

## Dashboard
![Client wise Monthly Growth % ( J&K Bank)](https://github.com/Abhijeetpatil-1998/JK-Bank-UPI-Transaction-Growth-Dashboard-Dec-2023-Nov-2025-/blob/main/Client%20wise%20Monthly%20Growth%20%25%20(%20J%26K%20Bank).jpeg)

## Project Insight
- Transactions grew from **77.7M (Dec 2023)** to **290.4M (Nov 2025)**, about **3.7x** in 23 months.
- **2024** was the stronger year, with growth in 11 of 12 months. Only **August 2024** declined (-2.38%).
- **Highest MoM growth:** January 2024 (**22.10%**), March 2024 (**22.06%**) and March 2025 (**18.12%**). March is strong in both years, likely due to financial-year-end activity.
- **Peak volume:** **July 2025** at **303.6M**.
- **Largest drop:** **August 2025** (**-8.19%**), followed by September 2025 (-3.64%).
- **2025 is more volatile:** 5 of 11 months declined (Jan, Feb, Aug, Sep, Nov), and volume has stayed below the July 2025 peak since then.
- **December 2025** shows -100% only because the month has no data yet; it is excluded from the analysis.

## Final Conclusion
Transaction volume has grown strongly over two years, but growth has slowed and become uneven in 2025, with volume still below the July peak. The reasons behind the August–September 2025 decline should be reviewed, and campaigns around seasonal peaks (such as March) can help sustain growth into the coming months.

## Tools Used
- Power BI Desktop (Data model, measures, visuals)
- Microsoft Excel (Data cleaning)
