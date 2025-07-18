<img width="1190" height="678" alt="#2" src="https://github.com/user-attachments/assets/8ce92042-f359-4e18-8f8c-cd6d781f1827" />## DSA DATA ANALYSIS PROJECT WORK SUMMARY USING MICROSOFT EXCEL TOOL
## AMAZON E-COMMERCE CASE STUDY
### Project Overview
This data analysis project aims to generate insight into the sales performance of the E-commerce project for Amazon trade year, it's product sales and customer reviews over the past trade year. By analyzing various parameters in the data received, we seek to gather enough insight to guide product improvement, marketing strategy and customer engagement.
### Data Source
The primary source of data used for this work is the “Amazon Case Study.csv” file shared to me.
### Data Cleaning and Preparation
In the initial phase, I performed the following processes;
- Data loading and inspection
- Data wrangling;
- - Handling missing data in cells and labelling them as “N/A”.
- - Reformatting data set.

These were all done to ensure data integrity with the rows being 1465 rows in total.

In the later phase, the worksheet was converted into a table, and some new columns were introduced using formulas including:
Price bucket, Potential revenue, Rating + Rating count, etc.

### Analysis tool
Microsoft Excel 2019 [Download Here](https://www.microsoft.com/en-us/microsoft-365/download-office)

### Exploratory Data Analysis (EDA)
By employing the use of pivot tables and calculated columns, I was able to answer the following questions:
- What is the average discount % by product category?
-  How many products are listed under each Category?
- What is the total number of reviews by category?
- Which products have the highest average rating?
- What is the average actual price vs discounted price by Category?
- Which product has the highest number of reviews?
- How many products have a discount of 50% and more?
- What is the distribution of product rating?
- What is the total potential revenue by Category?
- What is the number of unique products per price range bucket (<200, 200-500, >500)?
- How does the rating relate to the level of discount?
- How many products have fewer than 1000 reviews??
- Which Categories have products with the highest discount?
- Top 5 products in terms of average rating and reviews combined?

### ANALYSIS
Below are some DAX Expressions used during my analysis:
Creation of Pivot tables
<img width="1294" height="511" alt="1" src="https://github.com/user-attachments/assets/c597d63a-1853-4463-8f30-a24bc1b2e042" />
<img width="1258" height="577" alt="2" src="https://github.com/user-attachments/assets/30352328-a0a8-40b8-9adb-921cf740ed9a" />
<img width="1222" height="550" alt="3" src="https://github.com/user-attachments/assets/ace3cfad-5ecd-477c-bf93-7f9eb9ba85b1" />
<img width="1197" height="546" alt="4" src="https://github.com/user-attachments/assets/3fa6b9f7-93fb-4f18-811b-65bd364c4bb8" />


Creation of dashboard
Attached below is my interactive dashboard

![Project Data Chart](https://raw.githubusercontent.com/UniqueCas1/My-DSA-Data-Analysis-Project-Documentation-Using-Excel-Analytic-tool/main/%231.png)
<img width="1190" height="678" alt="#2" src="https://github.com/user-attachments/assets/ec61d1e5-f345-4cd2-a130-24781be94fa9" />



### RESULTS AND INSIGHTS

To see the full RESULT file [Amazon case study.xlsx](https://github.com/user-attachments/files/21251582/Amazon.case.study.xlsx)

According to my analysis, the top 5 products of the Amazon sales data set in terms of the average rating by customers and reviews combined are all products under ‘Electronics’ Category of products.

Amazon is making a good headway in the E-Market. Customers are satisfied based on the overall reviews and ratings, but there is need for improvement in the revenue generated by sales. T The relationship between the potential revenue generated by all product categories is exponential and has a approximate regular pattern in that, more revenue is peak at the product Categories with higher number of products and least in Categories with lowest number of products available. I hereby, advise that more stocking should be done in Categories with low availability of products such as Musical instruments, Home Improvements, toys and games, and Health and Personal Care

