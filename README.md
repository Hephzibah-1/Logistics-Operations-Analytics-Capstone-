# Logistics Operations Analytics: Capstone Project

An end-to-end analysis of a trucking company's operations, delivered as four interactive Power BI dashboards covering customers and revenue, driver performance, routes, and trips and fleet.

## Objective

To turn raw logistics data into decision-ready insights on how the business earns revenue, how drivers and routes perform, and how efficiently the fleet is used.

## Dataset

- **Source:** Logistics operations dataset provided through TS Academy
- **Scope:** 85,410 completed loads and trips, January 2022 to December 2024
- **Tables (14):** Customers, Routes, Loads, Trips, Delivery Events, Drivers, Driver Monthly Metrics, Trucks, Trailers, Truck Utilization Metrics, Fuel Purchases, Maintenance Records, Safety Incidents and Facilities

## Dashboards

| Dashboard | What it shows |
|-----------|---------------|
| **Customer & Revenue** | Total customers, revenue, average revenue per customer, top 10 customers, revenue by customer type and freight type, and actual revenue vs annual revenue potential |
| **Driver Performance** | Total drivers, driver-attributed revenue, on-time delivery rate, top drivers by revenue, experience groups, and trips vs revenue |
| **Route Performance** | Total routes, revenue and load volume by route, transit time groups, base rate per mile, and routes with the highest safety incident rates |
| **Trip & Fleet Operations** | Total trips, miles, trucks and trailers, top trucks by miles, maintenance cost by truck, equipment usage, and utilisation vs maintenance cost |

Each dashboard includes year slicers and a second slicer (account status, home terminal or customer type).

## Key Insights

- **Revenue:** about $262.5M from 200 customers, an average of $1.31M per customer. Revenue held steady at roughly $87M a year.
- **Low customer concentration:** the top 10 customers contribute only about 5.7% of revenue, so there is little dependence on any one account.
- **Customer mix:** Contract customers generate the most revenue (about 38%), followed by Spot (32%) and Dedicated (31%).
- **Freight mix:** Automotive leads at about 21% of revenue, followed by Food/Beverage (19%) and Retail (18%).
- **Untapped potential:** customers generate about $0.44M a year on average against a stated annual potential of about $2.69M, which points to room for growth within existing accounts.
- **Drivers:** the average on-time delivery rate across drivers is about 45%, and individual driver averages range from roughly 37% to 51%.
- **Routes:** Philadelphia to Seattle is the highest-earning route (about $10.1M), and average transit time across the 58 routes is about 2.1 days.
- **Fleet:** 85,410 trips covered about 122 million miles using 92 trucks and 180 trailers, split about 52% Dry Van and 48% Refrigerated.
- **Maintenance:** maintenance cost showed only a weak relationship with utilisation, so higher-use trucks were not necessarily the costliest to maintain.

## Tools Used

- **Power BI** for dashboards and visualisation
- **Power Query** for data cleaning and transformation
- **DAX** for measures such as Total Revenue, Average Revenue per Customer and Average On-Time Delivery Rate
- **Excel** for preliminary data review

## Process

1. Reviewed the 14 source tables and checked data quality
2. Cleaned and transformed the data in Power Query
3. Built relationships between tables and created DAX measures
4. Designed four dashboards, one for each business area
5. Summarised the findings above

## Files
- `CAPSTONE_PROJECT.pbix`: Power BI report
- `Capstone Combined Sheet.xlsx`
## Author

**Hephzibah Ajala**
www.linkedin.com/in/hephzibah-ajala-a21a0135a
