# Food Ordering Behaviour and Consumer Trends

A Tableau analysis of 50,000 food delivery orders, built as a capstone project.

## Problem Statement
The food delivery industry is highly competitive. Businesses hold large volumes of data but find it hard to see which factors drive order demand, customer spending and delivery efficiency. This project turns raw order data into clear, actionable insights using interactive Tableau dashboards.

## Users
- **Business Analyst:** studies demand, order value and customer behaviour across cities, cuisines and meal types.
- **Operations Manager:** studies delivery time and order volumes to find delays and improve efficiency.

## Dataset
- 50,000 orders across 6 cities: Mumbai, Pune, Bangalore, Delhi, Chandigarh, Hyderabad
- Key fields: Order Id, City, Cuisine, Meal Type, Company (who the customer ordered with), Restaurant Type, Age Group, Order Value, Delivery Fee, Rating Given, Time Taken To Order

## Tools
- Tableau Public
- GitHub

## Project Steps
1. Downloaded the dataset and loaded it into Tableau
2. Checked column names and data types
3. Created a calculated field (Age Group) and bins (delivery time, bin size 2)
4. Built 9 visualizations (listed below)
5. Combined them into one interactive dashboard with a City filter
6. Created a Tableau Story that walks from overview to insights to recommendation
7. Published the workbook to Tableau Public

## Visualizations
| # | Visualization | Chart Type |
|---|---------------|------------|
| 1 | KPI Demonstration (Total Orders, Total Order Value, Delivery Fee, Avg Rating) | Text table |
| 2 | Orders by City | Bar chart |
| 3 | Cuisine Popularity | Bar chart |
| 4 | Flavours Across Cities | Heatmap |
| 5 | Orders by Company Type and Meal Type | Bar chart |
| 6 | Revenue by Meal Type | Bar chart |
| 7 | Customer Rating by Meal Type | Pie chart |
| 8 | Age Group by Restaurant Type | Stacked bar chart |
| 9 | Delivery Time Distribution | Bar chart |

## Key Insights
- **KPIs:** 50,000 orders, about 27.4M in total order value, about 2.98M in delivery fees, and an average rating of about 3.
- **Cities:** Mumbai has the most orders, but all six cities are close (about 8,200 to 8,400 each), so demand is spread evenly.
- **Cuisine:** Desserts is the most ordered cuisine, followed closely by Fast Food. North Indian is the lowest, but the gaps are small, so no single cuisine dominates.
- **Flavours across cities:** Order counts per cuisine and city range from about 1,300 to 1,460, which shows consistent demand everywhere.
- **Revenue by meal type:** Breakfast, Snacks, Lunch and Dinner each bring in roughly 6.7M to 6.9M, so revenue is spread almost equally across the day.
- **Company type:** Orders are spread evenly across Alone, Friends, Family and Partner, with no group clearly leading.
- **Customer ratings:** Rating totals are almost equal across meal types (Breakfast 37,854 to Dinner 37,064).
- **Age groups:** Millennials lead all other groups, followed by Gen Z, Adults and Child.
- **Delivery time:** Most deliveries fall in the 2 to 12 range (about 7,000 orders per bin). The 0 and 14 bins are less common.

## Recommendations
1. Keep marketing balanced across all cities, with extra promotion in the top city.
2. Promote Desserts and Fast Food, and run offers on the lower-ordered cuisines to lift them.
3. Create targeted offers for Millennials and Gen Z, who order the most.
4. Monitor delivery times to find and reduce delays, and work on lifting the average rating above 3.

## Live Dashboard
https://public.tableau.com/app/profile/nayana.sonawane/viz/FoodOrderingBehaviourandconsumertrends/Foodorderingstory?publish=yes

## Repository Contents
- `.twbx` Tableau workbook
- Dataset (CSV)
- `README.md`
- `src/dashboard.py` and `requirements.txt` (Python version of the charts)
- `report/` (Word report)

## Author
Nayana Sonamwane
