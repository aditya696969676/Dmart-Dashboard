DMart Sales and Customer Insights Dashboard
Overview
This repository contains the source files and documentation for a Power BI dashboard designed to analyze DMart sales, customer, and order data. The dashboard provides actionable insights through visualizations such as sales trends, delivery time metrics, and customer demographics. It leverages DAX for custom measures and Power Query for data cleaning, ensuring accurate and dynamic reporting.

Features
Visualizations including sales trends, average delivery times, and payment method analysis.
DAX measures to calculate average delivery time and filter out cancelled orders.
Data cleaning in Power Query to resolve date inconsistencies and prepare datasets.
Interactive slicers for filtering by payment methods, dates, and other dimensions.
Data Sources
Product Table: Contains product details (ID, Name, MRP, Category, etc.).
Order Details Table: Includes order information (Order ID, Dates, Payment Method, etc.).
Customer Table: Holds customer data (ID, Age, Gender, State, etc.).
Data is sourced from DMart operational records (sample data included).
Setup Instructions
Install Power BI Desktop: Download and install the free version from powerbi.microsoft.com.
Download Repository: Clone or download this repository to your local machine.
Open the Project: Load the .pbix file (Power BI project file) in Power BI Desktop.
Update Data (Optional): Replace the sample data with your DMart dataset by connecting to the data source via the Power Query Editor.
Refresh Data: Click Refresh in Power BI to load the latest data.
Usage
Navigate the dashboard to explore sales performance, customer insights, and delivery efficiency.
Use slicers to filter data by payment method, year, or region.
Customize visuals by adjusting measures or adding new ones in the DAX editor.
Technologies Used
Power BI: For dashboard creation and visualization.
DAX: For calculating measures like average delivery time.
Power Query: For data cleaning and transformation.
Contributing
This project is for personal use and learning purposes. Contributions are welcome—feel free to fork the repository, make improvements, and submit pull requests.

Credits
Developed by [Your Name] as a portfolio project.
Built on data from DMart (sample dataset used for demonstration).
