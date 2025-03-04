# What is this dashboard for and for whom?

This dashboard provides business owners, sales managers, and financial analysts with insights into sales performance, production efficiency, and financial trends. It helps visualize key metrics, identify revenue patterns, monitor costs, and optimize decision-making for better market positioning.

### 🔥 Key Benefits
This Excel Product Manager Dashboard offers several advantages for businesses and individuals managing product stock and sales efficiently:

- **Comprehensive Product Tracking** – Keep an accurate record of stock levels, sales, and inventory movements in real time.
- **Time-Saving Automation** – Automates calculations, updates, and visualizations, reducing manual data entry and minimizing errors.
- **Insightful Data Visualization** – Provides easy-to-understand charts and tables for quick decision-making and performance analysis.
- **Dynamic Filtering & Customization** – Allows users to filter data dynamically and customize reports based on business needs.
- **Sales & Revenue Monitoring** – Tracks sales trends, revenue generation, and profit margins to optimize business performance.
- **User-Friendly Interface** – Designed with simplicity in mind, ensuring accessibility for both beginners and advanced Excel users.

This dashboard serves as a powerful tool for business owners, product managers, and analysts looking to streamline their inventory and sales processes.

# 🎨 User Interface & User Experience (UI/UX)

This Excel Product Manager Dashboard is designed with a clean and intuitive user interface to enhance usability and efficiency.

### 🏗 Core Components of the Dashboard

The dashboard consists of several key sections that provide seamless data visualization and management:


- ### Dashboard
    ![Product_Manager_Dashboard](https://github.com/user-attachments/assets/7552533b-2656-4208-bbc6-ee27b4491c96)

    - **Main Dashboard**  
    A high-level overview displaying key metrics such as total stock, sales trends, and revenue.
    - **Stock Management Table**  
    A structured table to track product inventory, including stock levels, reorder alerts, and supplier details.
    - **Sales Performance Panel**  
    Provides insights into sales volume, best-selling products, and revenue comparisons. (*Moreover, the graphs of external sales and internal sales can be given separately. Because the sales_type is automatically written in a hidden column on the sales page according to the company name selected in that row, and the graphs can be separated by filtering according to type.*)
    - **Dynamic Filtering Panel**  
    Allows users to apply filters by product category, date, or custom criteria for more precise analysis.


- ### Report
    ![Product_Manager_Report](https://github.com/user-attachments/assets/fccf0cd0-1c99-44c8-9ffe-845d657fd2f6)

    - **Working logic**  
    The day range of the current week is automatically calculated on the report page. And that week's purchases, production, domestic and foreign sales are brought together with their important titles.  
      
        If there is no data entry for that week, it gives a #CALC! error. Of course, if there is a warning message that you want to print simply from the formula in the cell, you can print it.
    - **Best Part**  
    The best part about this page is that you don't even have to touch it in any way. It can automatically give you a weekly report.


- ### Sales
    ![Product_Manager_Sales](https://github.com/user-attachments/assets/f95ab0a2-0e35-4c91-bb50-4f229fb5413a)

    
    - **Working logic**  
    The **Sales** page is designed to systematically record and track all sales transactions. It provides an organized structure to capture essential sales details, such as the date, customer, material name, quantity, unit, price, and total amount. The logic behind this page ensures that sales data is efficiently recorded, analyzed, and used for reporting.  
    
        When we start using it under normal conditions, we hide the columns after the checkboxes.
    
    - **Automated Weekly and Monthly Tracking**  
    Each sale entry is automatically assigned a Week Number and Month based on the sale date. This allows for seamless weekly and monthly reporting in the dashboard and report sections.

    - **Highlighted Lines**  
    There are two different checkboxes on this page. One is to mark it as sold out and the other is to mark it as invoiced.

    - **Best Part**  
    One of the best parts is that as soon as you select the material you want to sell, the unit and unit price of that material are automatically displayed. I know it's a very simple automation, but I had no idea it would make life this easy.

- ### Production
    ![Product_Manager_Production](https://github.com/user-attachments/assets/6f732d8d-764e-4f85-98b7-43869d9ddad3)

    
    - **Working logic**  
    You can enter data by selecting the products specified for production on the dropdown data page.

- ### Purchases
    ![Product_Manager_Purchases](https://github.com/user-attachments/assets/e4bcc3e1-c724-4eac-9848-0c9128672d48)

    
    - **Working logic**  
    Similarly, data entry can be provided by selecting company names and material names from the list. Also, you do not have to select the company name from the list, you can write it there manually.

- ### Dropdown Data
    ![Product_Manager_DropdownData](https://github.com/user-attachments/assets/ed1801c5-7559-454e-bab9-b9fbb837da9f)

    - **Working logic**  
    Almost all dropdown lists pull their data from the tables on this page. You can change many data information such as material name, unit, unit price and starting stock.  

    - **Best Part**  
    At the same time, many data sets that we pull to the dashboard page are also automatically collected on this page.

- ### Calculations
    ![Product_Manager_Calculation](https://github.com/user-attachments/assets/11e9ce28-3052-4a7d-bc08-d9d700dcace9)


    - **Working Logic**  
    This is also a page that we keep. It is a page where the formulas of the variable values ​​on the left side of the dashboard page are kept. There are also some filtered pivot tables of sales values.

# What I Learned

I have significantly strengthened my Excel experience throughout this adventure:

- **📊 Advanced Formula Mastery:**  
Leveraged powerful formulas like IF, SUMIFS, INDEX-MATCH, COUNTIFS, DATE, EOMONTH, VSATCK, FILTER, XLOOKUP, UNIQUE and TEXT functions to automate calculations and dynamically retrieve data based on specific conditions.
- **🔄 Pivot Table Proficiency:**  
Transformed raw datasets into insightful reports using Pivot Tables, efficiently summarizing sales, purchases, and production data with calculated fields and dynamic filters.
- **🎨 Conditional Formatting Expertise:**  
Applied rule-based color coding to highlight important trends, flag unusual values, and visually distinguish critical sales transactions and overdue invoices.
- **🔍 Smart Filtering & Sorting:**  
Utilized AutoFilters, Custom Sorting, and Advanced Filters to extract meaningful insights from large datasets and streamline data analysis.
- **📑 Automated Reporting & Dashboarding:**  
Created dynamic reports and interactive dashboards, integrating formulas, charts, and conditional formatting to provide real-time business insights.
