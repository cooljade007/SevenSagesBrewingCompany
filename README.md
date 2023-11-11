
# Seven Sages Brewing Company 

## Overview 

This is Udacity’s first project under the Nanodegree Program Data Analysis and Visualization with Microsoft Power BI and focuses on preparing and modeling data using Power BI. (Completed on October 11, 2023) 

For our first project, we created a data model and Power BI report for a fictional company called Seven Sages Brewing Company that combines information from all over the company. The goal of this project was to make it possible for the company’s CFO to quickly review and analyze what beers sell well and which ones generate the highest profitability. 

(This project already had end results of how our report should look like and we were tasked with the goal to recreate the report using the sources given.) 

## Sources 

The source material for this project can be found under the folder called “source files”. 

- <b> Promotional document:</b> The sales department has provided a promotional document that lists all the company’s current offerings, ratings, and servings sizes. 

- <b> Purchases:</b> An operations assistant has provided data on purchases, in the form of multiple Excel spreadsheets 

- <b> Customer records:</b> IT has provided customer records. They had to download these separately, but they have assured us that they are up to date. 

- <b> Metrics documentation:</b> The CFO has provided her metrics documentation that she’s been compiling on sales, costs, and servings (per  

## ETL 

#### Data Cleanup 

- Promoted first rows to headers as needed 

- Reviewed data types for each field to ensure that they are identified correctly 

- Renamed any ambiguous queries so that they can be easily identified during data modeling 

- Renamed any unclear columns so you can easily find and use them 

- Removed any or all blank rows 

- Deleted unnecessary columns 

- Corrected any obvious typos that will impact report results 

#### Combining Data 

- Merged dimension tables with a 1-to-1 relationship 

- Merged CFO Metrics Tracker and SSBC Product Offerings to create the Product table 

- Combined Sales files under the “Monthly Sales Logs” folder into one Sales table. (Files include columns of the name.) 

## Date Table Creation 

Created a dynamic date table that starts at the beginning of the calendar year of the earliest Sales year and ends at the end of the calendar year for the latest year on the Sales table. 

This continuous table includes the following columns: 

- Calendar Month Number and Name 

- Calendar Year 

- Fiscal Period 

- Fiscal Year 

- Fiscal Quarter (example: Q2-FY2020) 

(Seven Sages’ Fiscal year begins on October 1st and runs until September 30th. )

## Data Model 

![DataModel](https://github.com/cooljade007/SevenSagesBrewingCompany/assets/42302130/30969b43-0a77-49da-acc0-ffb560b1ec51)

Fact Table 

- Sales 

Dimension Tables 

- Products 

- Customers 

- Calendar 

- Exchange Rates 

## Measures 

- Total Sales ($USD) 

- Cost of Sales ($USD) 

- Gross Profit Margin (%) 

- Sales ($CAD) 

- Unit Sales by Product (%, USD) 

- Gross Profit by Product (%,USD) 

## Report 

#### Tab #1 

![Tab1_SalesAndGPM](https://github.com/cooljade007/SevenSagesBrewingCompany/assets/42302130/63e4fdee-2eff-442c-b22b-862a1de801b9)

- Sales and GPM: This tab summarizes the sales by customer and customer type across quarters. 

#### Tab #2 

![Tab2_GrossProfitAndUnitSales](https://github.com/cooljade007/SevenSagesBrewingCompany/assets/42302130/e29d9a0a-c98a-4e09-b832-cfd3ed8cb599)

- Gross Profit and Unit Sales: This tab would simply summarize the percentages of gross profit and unit sales by product. 

#### Tab #3 

![Tab3_SO1_ProductType](https://github.com/cooljade007/SevenSagesBrewingCompany/assets/42302130/004db1bf-7d29-4cfb-9f14-a02f5cf98898)

- Extra: This tab shows what product type is most profitable per serving for SSBC. 

 

 

 

 
