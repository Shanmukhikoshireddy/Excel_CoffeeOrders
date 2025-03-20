# Excel_CoffeeOrders
# Coffee Orders Data Cleanup

## Overview
This repository contains a dataset of coffee orders, customers, and sales data. The dataset has been cleaned and structured for better analysis and visualization. The original data contained missing values, incorrect headers, and inconsistent formatting, which have been addressed in the cleaned version.

## Dataset Structure
The dataset is organized into the following sheets:

- **TotalSales**: Aggregated sales data by year and month.
- **Charts**: Summary sales data for visualization.
- **Orders**: Detailed coffee order records including customer, product, and sales details.
- **Customers**: Customer information including contact details and location.
- **Products**: Coffee product details such as type, roast level, size, and pricing.
- **Dashboard**: A visual representation of key metrics, including total sales, top-selling products, and customer insights.

## Cleaning Process
The following steps were taken to clean and standardize the data:
1. Removed empty or unnecessary rows from `TotalSales`.
2. Ensured column headers were properly aligned.
3. Filled missing `Email` values in `Orders` and `Customers` with placeholders.
4. Converted numerical columns (`Sales`, `Unit Price`, `Profit`) to the correct data type.
5. Removed inconsistent data entries.
6. Standardized date formats and order IDs.

## Dashboard
The dataset includes a `Dashboard` sheet designed for easy data visualization. The dashboard highlights:
- **Total Sales Trends**: Monthly and yearly sales performance.
- **Top-Selling Products**: Best-selling coffee types and roast levels.
- **Customer Insights**: Analysis of repeat customers and their preferences.
- **Geographic Sales Distribution**: Sales performance by country and region.

This dashboard can be further customized and analyzed using Excel, Power BI, or Tableau to gain deeper business insights.

## Usage
- The cleaned dataset is available in `cleaned_coffeeOrdersData.xlsx`.
- It can be used for data analysis, visualization, and reporting on coffee sales trends.
- Compatible with Python (pandas), Excel, and BI tools like Power BI or Tableau.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/coffee-orders-data.git
   ```
2. Open the cleaned dataset in Excel or load it into Python using pandas:
   ```python
   import pandas as pd
   df = pd.read_excel("cleaned_coffeeOrdersData.xlsx", sheet_name=None)
   ```
3. Perform analysis or create visualizations as needed.

## License
This dataset is shared for educational and analytical purposes. Modify and use it as needed.

## Contributors
- [Shanmukhi_koshireddy]
- Open to contributions and improvements!

Feel free to raise issues or pull requests for further enhancements.

