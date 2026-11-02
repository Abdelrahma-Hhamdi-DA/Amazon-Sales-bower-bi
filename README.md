Amazon Sales Analysis | Power BI
An interactive Power BI dashboard project focused on analyzing Amazon product sales, tracking key performance indicators, and exploring sales trends across time and product categories.
Project Overview
This project analyzes an Amazon products sales dataset to turn raw sales data into clear, interactive business insights. The report provides an overview of sales performance, product activity, customer reviews, and category-level contribution.

The dashboard was built using Power BI, with Power Query for data preparation and data modeling to organize the analytical model and support time-based analysis.
Business Objectives
- Monitor overall sales performance through key performance indicators.
- Compare Year-to-Date (YTD) and Quarter-to-Date (QTD) sales.
- Track the number of products sold and customer reviews.
- Identify monthly and weekly sales trends.
- Compare sales performance across product categories.
- Highlight the top-performing products by sales and review volume.
- Allow users to explore the report using interactive filters.
Tools & Technologies
Tool	Purpose
Power BI	Dashboard development and interactive data visualization
Power Query	Data cleaning, transformation, and preparation
Data Modeling	Building table relationships and an analytical data model
DAX	Creating measures and business calculations
Date Table	Supporting calendar-based and time-intelligence analysis


Data Preparation
The dataset was prepared in Power Query before being used in the report. The preparation workflow included reviewing the source columns, checking data types, and applying the required transformations to make the data suitable for analysis.

The main dataset includes fields such as:
- Product Category
- Product Description
- Price (Dollar)
- Number of Reviews
- Order Date
- Shipment
The fields listed above are based on the columns visible in the project screenshots.
Data Modeling
A dedicated Date Table was created and connected to the Amazon_Data table through the order date.

The model uses a one-to-many relationship, with the Date Table on the one side and the sales data on the many side. This structure supports consistent filtering and time-based reporting.

The Date Table includes calendar attributes such as:
- Date
- Month Name
- Month Number
- Quarter (QTR)
- Quarter Number
Dashboard Features
The report contains the following sections:
1. Key Performance Indicators
- YTD Sales: $2.18M
- QTD Sales: $811.09K
- YTD Products Sold: 27.75K
- YTD Reviews: 19.42M
2. Sales Trends
- Monthly sales trend to show how performance changes throughout the year.
- Weekly sales visualization to explore sales fluctuations across the weeks.
3. Product Category Analysis
A category-level table compares:
- YTD Sales
- QTD Sales
- Percentage of YTD Sales
This helps identify the categories contributing most to overall sales.
4. Top Products Analysis
- Top 5 products ranked by YTD Sales.
- Top 5 products ranked by YTD Reviews.
5. Interactive Filters
Users can filter the report by:
- Product Category
- Quarter (QTR)
These slicers make it easier to focus on specific parts of the dataset and explore the dashboard dynamically.
Key Dashboard Highlights
- Men Shoes is the leading category by YTD Sales in the displayed report.
- The dashboard provides both monthly and weekly views of sales performance.
- Product rankings make it easier to identify leading products by sales and review volume.
- Category and quarter filters allow users to investigate performance from different perspectives.
These highlights describe the figures and visuals shown in the provided dashboard screenshot. Results may change when filters are applied.
Project Structure
A suggested GitHub repository structure:
amazon-sales-analysis/
│
├── README.md
├── Dashboard/
│   └── Amazon_Sales_Analysis.pbix
├── Data/
│   └── README.md
└── Images/
    └── dashboard-screenshot.png
Add your actual .pbix file and dashboard screenshot to the corresponding folders before publishing. If the dataset cannot be shared, keep it private and add a short note in Data/README.md describing its source and availability.
How to Explore the Project
1. Download or clone this repository.
2. Open Dashboard/Amazon_Sales_Analysis.pbix using Power BI Desktop.
3. If the source dataset is not embedded in the PBIX file, update the data source path when prompted.
4. Refresh the data if required.
5. Use the Product Category and QTR slicers to interact with the report.
Skills Demonstrated
- Data cleaning and transformation
- Power Query
- Data modeling and table relationships
- Date table creation
- DAX measures and KPI reporting
- Time-based sales analysis
- Interactive dashboard design
- Business-focused data visualization
Author
Abdelrahman Hamdi
Aspiring Data Analyst
If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.
