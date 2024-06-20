# Financial Data Analysis Project

This project involves analyzing financial data from a sample dataset using various data visualization and statistical analysis techniques.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Data Overview](#data-overview)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Statistical Analysis](#statistical-analysis)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project demonstrates how to:
- Import and preprocess financial data using pandas and numpy.
- Create various visualizations using matplotlib and seaborn.
- Perform statistical analysis including T-tests and ANOVA.

## Installation
To get started, clone this repository and install the required packages:

```bash
git clone https://github.com/yourusername/financial-data-analysis.git
cd financial-data-analysis
pip install -r requirements.txt
```

## Data Overview
The dataset used in this project is `Financial Sample.xlsx`, which contains financial data across different countries, products, and segments. Below is a brief overview of the dataset:

### Columns:
- **Id Number**: A unique identifier for each record.
- **Segment**: The market segment.
- **Country**: The country where the sales were made.
- **Product**: The product sold.
- **Discount Band**: The discount band applied.
- **Units Sold**: The number of units sold.
- **Manufacturing Price**: The price of manufacturing the product.
- **Sale Price**: The selling price of the product.
- **Gross Sales**: The total gross sales amount.
- **Discounts**: The total discount amount.
- **Sales**: The net sales amount.
- **COGS**: Cost of Goods Sold.
- **Profit**: The profit made.
- **Date**: The date of the sale.
- **Month Name**: The month of the sale.
- **Year**: The year of the sale.

### Basic Statistics:
The table below summarizes some basic statistics of the dataset:

| Statistic       | Value             |
|-----------------|-------------------|
| Total Records   | 700               |
| Total Countries | 5                 |
| Total Segments  | 5                 |
| Total Products  | 6                 |

### Sample Data:
Here is a sample of the dataset:

<table>
  <tr>
    <th>Id Number</th>
    <th>Segment</th>
    <th>Country</th>
    <th>Product</th>
    <th>Units Sold</th>
    <th>Sales</th>
    <th>Profit</th>
  </tr>
  <tr>
    <td>1000</td>
    <td>Government</td>
    <td>United States of America</td>
    <td>Carretera</td>
    <td>1618</td>
    <td>25888</td>
    <td>9708</td>
  </tr>
  <tr>
    <td>1001</td>
    <td>Midmarket</td>
    <td>Canada</td>
    <td>Montana</td>
    <td>1321</td>
    <td>15852</td>
    <td>2642</td>
  </tr>
  <tr>
    <td>1002</td>
    <td>Channel Partners</td>
    <td>Germany</td>
    <td>VTT</td>
    <td>512</td>
    <td>11520</td>
    <td>1280</td>
  </tr>
  <tr>
    <td>1003</td>
    <td>Enterprise</td>
    <td>Mexico</td>
    <td>Paseo</td>
    <td>729</td>
    <td>7290</td>
    <td>3645</td>
  </tr>
  <tr>
    <td>1004</td>
    <td>Small Business</td>
    <td>France</td>
    <td>Velo</td>
    <td>1040</td>
    <td>24960</td>
    <td>12480</td>
  </tr>
</table>

For a more detailed view, you can refer to the dataset file included in the `data` folder.
