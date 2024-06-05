# Amazon Shopping Sales Analysis with Power BI

## Project Overview

This project leverages Power BI to analyze Amazon shopping sales data, offering insights into sales performance, customer behavior, and market trends through interactive visualizations and reports. The primary dashboard provides an overview of key metrics, segment performance, market distribution, and profit analysis.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Requirements](#requirements)
3. [Data Sources](#data-sources)
4. [Setup Instructions](#setup-instructions)
5. [Power BI Dashboard Features](#power-bi-dashboard-features)
6. [Usage Instructions](#usage-instructions)
7. [Contributing](#contributing)
8. [License](#license)

## Project Structure

```
amazon-shopping-sales-analysis/
├── data/
│   ├── raw/
│   ├── processed/
│   └── data_dictionary.xlsx
├── reports/
│   ├── PowerBI_Sales_Analysis.pbix
│   └── screenshots/
│       └── dashboard_screenshot.png
├── scripts/
│   └── data_preprocessing.py
├── README.md
└── requirements.txt
```

- **data/**: Contains raw and processed data files.
- **reports/**: Contains the Power BI report file and screenshots.
- **scripts/**: Contains data preprocessing scripts.
- **README.md**: Project documentation.
- **requirements.txt**: List of required Python packages for data preprocessing.

## Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- Python 3.x (if data preprocessing is required)
- Python libraries listed in `requirements.txt` (use `pip install -r requirements.txt`)

## Data Sources

The data sources used in this project include:

- **Sales Data**: Detailed information on sales transactions (e.g., order ID, product ID, customer ID, sales amount, date of purchase, etc.).
- **Customer Data**: Demographics and behavior data of customers (e.g., customer ID, age, gender, location, etc.).
- **Product Data**: Details of products (e.g., product ID, category, price, etc.).

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KodavatiAnisha/amazonReport/new/main?filename=README.md
   cd amazon-shopping-sales-analysis
   ```

2. **Install Python dependencies** (if needed for data preprocessing):
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the data**:
   - Place raw data files in the `data/raw/` directory.
   - Run the data preprocessing script (if required) to clean and transform the data:
     ```bash
     python scripts/data_preprocessing.py
     ```

4. **Open the Power BI report**:
   - Launch Power BI Desktop.
   - Open the `PowerBI_Sales_Analysis.pbix` file located in the `reports/` directory.

## Power BI Dashboard Features

The Power BI dashboard includes the following features:

- **Sales Projection**: Overview of sales projections.
- **Product Units**: Total units of products sold.
- **KPI**: Key performance indicators.
- **Returns**: Number of product returns.
- **Sales by Segment**: Sales distribution across different customer segments (Consumer, Corporate, Home Office).
- **Sales by Market**: Sales distribution across different markets (Asia Pacific, Europe, USCA, LATAM, Africa).
- **Sum of Sales by Region**: Geographical distribution of sales on a world map.
- **Profit by Customer Name**: Profitability analysis by individual customers.
- **Bottom 5 Profit by Product**: Products with the lowest profit margins.
- **Top 5 Profit by Product**: Products with the highest profit margins.

## Usage Instructions

1. **Interact with the Dashboard**:
   - Use filters and slicers to explore data by different dimensions (e.g., year, product category, customer segment).
   - Hover over visualizations to see detailed tooltips.
   - Drill down into specific data points for more granular insights.

2. **Customize the Dashboard**:
   - Modify existing visualizations or create new ones to address specific business questions.
   - Update data connections if new data sources are added.

## Contributing

We welcome contributions to enhance the project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your forked repository.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to reach out with any questions or feedback. Happy analyzing!
