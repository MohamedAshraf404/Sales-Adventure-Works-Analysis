# Sales Data Analysis Using Power BI  

This project involves creating a fully interactive dashboard using **Power BI** to analyze the sales data of **Adventure Works**, a fictional company specializing in product sales. The goal of the project was to transform raw data into actionable insights by designing interactive and visually appealing reports to support management decision-making.  

![ٍSales Dashboard]([path_to_image](https://github.com/MohamedAshraf404/Sales-Adventure-Works-Analysis/blob/a81aad6245922c36511f81119f2f0bed84b62c03/Sales%20Report.jpg))

## Steps Undertaken  

### Data Connection  
- Connected to the **Adventure Works** database using **DirectQuery** mode to ensure real-time data updates.  

### Data Import  
- Imported essential tables such as `SalesOrderHeader`, `SalesOrderDetail`, `Product`, `ProductCategory`, and others to analyze sales and product data.  

### Custom Tables Creation  
- Created a `Status` table using the **ufnGetSalesOrderStatusText** function to classify order statuses.  
- Built a `Dates` table using **Power Query** to facilitate time-based data analysis.  

### Data Cleaning  
- Renamed tables and columns for better clarity and usability.  
- Removed unused columns to simplify the dataset.  
- Resolved errors in values such as `TotalDue`, `Freight`, `Tax`, and `Subtotal`.  

### Star Schema Design  
- Designed a star schema model to efficiently connect tables, enabling easier data analysis and reporting.  

### Measure Creation  
Developed key measures to enhance analysis, including:  
- **No. Orders**: Total number of orders  
- **Total Subtotal**: Total sales  
- **Total Tax**: Total tax amount  
- **Total Freight**: Total shipping cost  
- **Total Due**: Total amount due  
- **Total Quantity**: Total quantity sold  

### Dashboard Design  
- Created a three-page interactive dashboard featuring a variety of charts and interactive tables.  
- Added navigation between pages using **Bookmarks** to improve user experience.  
- Designed an intuitive and visually appealing user interface using appropriate colors and layout.  

### Top Sales Representatives Analysis  
- Included a chart displaying the top 10 sales representatives based on the number of orders or total revenue, with filtering options available through the **Filter Pane**.  

## Project Highlights  
- **High Interactivity**: Users can filter and explore data based on their needs.  
- **Creative Design**: Focused on a visually appealing and user-friendly interface.  
- **Comprehensive Analysis**: Reports cover all aspects of sales data, from orders to taxes and shipping.  
- **Scalability**: Easy to add more data or measures in the future.  

## Results  
The project provided a comprehensive analysis of sales data, enabling the company to identify trends, improve performance, and make data-driven decisions.  

This project showcases my ability to transform complex data into clear and actionable insights using **Power BI**, with a strong focus on interactivity and creative design.
