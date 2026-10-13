# Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist**, available on Kaggle:

[https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download)

## Why the Raw Data Is Not Stored Here

The raw CSV files are not included in this repository to keep the project lightweight and to avoid duplicating a public dataset that can already be downloaded directly from the original source.

Please download the dataset from Kaggle before opening and refreshing the Power BI project.

## Main Files Used

The Power BI model primarily uses the following Olist tables:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_customers_dataset.csv`
- `olist_products_dataset.csv`
- `olist_order_payments_dataset.csv`
- `product_category_name_translation.csv`

Depending on how you extend the project, additional Olist tables such as sellers or geolocation can also be used.

## Setup

1. Download the dataset from Kaggle.
2. Extract the CSV files to a local folder.
3. Open the Power BI file:

```text
dashboard/olist_ecommerce_analytics.pbix
```

4. If Power BI cannot find the source files, open **Power Query** and update the file paths to the folder where you extracted the dataset.
5. Refresh the model.

## Note

The dataset is provided by Olist via Kaggle. This repository contains only the Power BI project, documentation, screenshots, and related portfolio material.
