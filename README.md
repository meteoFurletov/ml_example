# Olist E-commerce Dataset Analysis

Hello! This project serves as a practical guide to machine learning using the Brazilian E-Commerce Public Dataset from Olist. The dataset's richness and multifaceted nature make it ideal for demonstrating various machine learning techniques with Python's scikit-learn, pandas, and seaborn libraries. The project covers data loading, preprocessing, exploratory data analysis, and the implementation of regression, classification, and clustering models, providing a comprehensive approach to understanding and applying machine learning in an e-commerce context.

## Project Structure

- **data/**: Contains the raw datasets in CSV format.
  - `olist_customers_dataset.csv`
  - `olist_geolocation_dataset.csv`
  - `olist_order_items_dataset.csv`
  - `olist_order_payments_dataset.csv`
  - `olist_order_reviews_dataset.csv`
  - `olist_orders_dataset.csv`
  - `olist_products_dataset.csv`
  - `olist_sellers_dataset.csv`
  - `product_category_name_translation.csv`
- **notebooks/**: Contains Jupyter notebooks for data analysis.
  - `example.ipynb`
  - `solution.ipynb`

## Getting Started

1. **Clone the repository**:
    ```sh
    git clone https://github.com/meteoFurletov/ml_example.git
    cd ml_example
    ```

2. **Setup and activate the virtual environment**:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Datasets

The datasets are sourced from the Olist e-commerce platform and include:

- **Customers**: Information about customers.
- **Geolocations**: Geographical data for customer locations.
- **Order Items**: Details of items in each order.
- **Payments**: Payment information for orders.
- **Reviews**: Customer reviews for orders.
- **Orders**: General information about orders.
- **Products**: Information about products.
- **Sellers**: Information about sellers.
- **Product Category Translations**: Translations for product category names.

## Notebooks

- **example.ipynb**: An example notebook demonstrating basic data analysis.
- **solution.ipynb**: The main notebook containing the solution to the analysis problem.
