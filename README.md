![logo-removebg](https://github.com/user-attachments/assets/be7bfd85-516d-4e72-a264-092954517171)
# ASCES Products Dashboard

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
