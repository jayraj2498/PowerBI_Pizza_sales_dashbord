## This project demonstrates the creation of a project powertbi dashboard of jan 15 to dec 15 data 
## It covers data extraction from a SQL database, data processing and DAX queries, dashboard design, and sharing ## insights. The project aims to provide real-time insights into credit card operations, enabling stakeholders to ## monitor and analyze performance efficiently.  

- Devlope Comprehensive yearly dashborad provides real time weekly insight  insights 
- insight into key performance matrix and trend 
- Enable to stasck honder to moniter and analyze credit card operation effectively  


## 1. Project objective
## 2. Data from SQL
## 3. Data processing & DAX
## 4. Dashboard & insights
## 5. Export & share project

### Project Objective

- To develop a Pizza Sales card Yearly  dashboard that
provides real-time insights into key
performance metrics and trends,
enabling stakeholders to monitor
and analyze credit card operations
effectively.

### step. 1 import dta from sql   

### step.2 load data tables from sql 

### step. 3 Data processing and DAX queries   

 Dax Query 
    - Order day = UPPER(LEFT(pizza_sales[Day Name],3))
    - Order Month = UPPER(LEFT(pizza_sales[Month Name],3)) 
    - Total Orders = DISTINCTCOUNT(pizza_sales[order_id])
    - Total Pizzas Sold = sum(pizza_sales[quantity]) 
    - Total Revenue = sum(pizza_sales[total_price])
    - Avg order value = [Total Revenue]/[Total Orders] 
    - Avg Pizzas Per Order = [Total Pizzas Sold]/[Total Orders]  





# Project Insights For  1 year 

## Days : Orders are Highest on weekends Friday saturday 
## Monthly : There are Max orders in the month of Julu and Janurary 
- • Overall revenue is 817.86 K 
- • Average order value 38.81 
- • Total Orders 21350 
- • Avg Pizza per order 2.23
- • Large Pizza Sales 45.56 % 
- • Large Pizza Categories 26.91 % 


## Sales Performance 
### Categories 

####  Classic categories Countributes to Maximum Sales & Total Orders 
#### Large Size Pizza Countributes To Max sales 



 



## This project demonstrates the creation of a comprehensive credit card dashboard using Power BI. It covers data extraction from a SQL database, data processing and DAX queries, dashboard design, and sharing insights. The project aims to provide real-time insights into credit card operations, enabling stakeholders to monitor and analyze performance efficiently.  
