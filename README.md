# ASCES-Products-Dashboard


https://private-user-images.githubusercontent.com/161084744/403507146-c69b184b-5ef2-4b0b-984c-481e06adbb7d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzY5NjAwNzAsIm5iZiI6MTczNjk1OTc3MCwicGF0aCI6Ii8xNjEwODQ3NDQvNDAzNTA3MTQ2LWM2OWIxODRiLTVlZjItNGIwYi05ODRjLTQ4MWUwNmFkYmI3ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMTE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDExNVQxNjQ5MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zNjk4ZWRjNDY3YWViOWFkNTc4NmI5ODE3MjVjYWUyNjVhZTQzYTY4NzJiOGMxZThiNDk5OWRhYjNiY2JkNWQyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Us5Ei1iA-voL04fdqLCN2VTIcCoOi5bRfihxGCU1r5U

## Problem Statement

This dashboard helps the stakeholders at ASCES Sounds understand their Products better. It helps the them know how their overall business and individual products have performed from 2022 to 2023. Through different categorization - Customer Type, Countries, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the how the discount bands affects the company revenue. Overall revenue was displayed and several product information & details such cost price, sales price and so on. 

### Steps followed 

- Dataset Analysis 

Load data into SMSS, I had 3 tables, discount data, product data and product sales to analyze and join to form single dataset needed for reporting. SQL queries was used to derive this. 

Additional columns relevant for insights were formed. These are Month, Year from date column, discounted revenue, total cost and profits. Discounts applied on each sale was achieved by joining the discount month bands to their respective months.

- Power BI Dashboard

Dax queries was used to derive the year on year profits and units sold and displayed in percentage. Proper formating and conditions were administered to ensure valid presentation.

New table was created to cater as a date table.

Image URL was used on Slicers adding good looks to the overall dashboard. Measures were used on columns such as Brands, Description and Products to ensure information is displayed accurately on selection.

#### Reference
- Absent data https://www.youtube.com/watch?v=6MOyrQLCi3w
- Chat GPT https://chatgpt.com/c/677ffcfb-6c4c-8011-ad11-233927e8a549
