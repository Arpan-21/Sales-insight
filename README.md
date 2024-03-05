# Sales-insights using Tableau

## E-T-L process
- Extracted data of an organization (FY2017-2020) who has market all over India.
- As data is extracted using SQL so we have to clean the irrelevant and redundant instances to get the analyze better like currencies, minimum sales amount.
- After cleaning the data we Load the data in Tableau by connecting it to our MySQL server and use it for getting the sales insight of that organization.

## Join
- We will inner join all the tables to get easily data insights.
- To get better resuts, we normalize the sales amount by converting it into the same currencies. here I converted INR -> USD.

## Worksheets
- In tableau we work on worksheets and for analysis use that worksheets at one place in our dashboard.
- I created charts on **Revenue by Market** , **Profit Margin by Market** , **Top 5 Customers** , **Top 5 products** , **Revenue by year** , **Profit trend**
- After that I created a dashboard for better analyzing using in-built filter feature of Tableau, see screenshots below:

## Sales Dashboard
  ![Sales](https://i.ibb.co/B3T48NG/Sales.png)

## Proft Trend Dashboard
  ![Profit](https://i.ibb.co/TrP1YKT/SS1.png)
