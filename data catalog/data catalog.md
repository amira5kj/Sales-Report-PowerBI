## Sales Data Catalog

### 1. sales_orders

- **Purpose:** Stores transactional sales data including order details, customer information, product details, and financial metrics.

- **Columns:**

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| row_id | INT | Unique identifier for each row in the dataset. |
| order_id | NVARCHAR(50) | Unique identifier assigned to each sales order. |
| order_date | DATE | The date when the order was placed. |
| ship_date | DATE | The date when the order was shipped to the customer. |
| ship_mode | NVARCHAR(50) | The shipping method used for the order (e.g., Standard Class, Second Class). |
| customer_id | NVARCHAR(50) | Unique identifier assigned to each customer. |
| customer_name | NVARCHAR(100) | Full name of the customer placing the order. |
| segment | NVARCHAR(50) | Customer segment classification (e.g., Consumer, Corporate, Home Office). |
| country | NVARCHAR(50) | The country where the customer is located. |
| city | NVARCHAR(50) | The city where the customer resides. |
| state | NVARCHAR(50) | The state where the customer resides. |
| postal_code | INT | Postal code associated with the customer's address. |
| region | NVARCHAR(50) | Sales region classification (e.g., South, West, Central, East). |
| product_id | NVARCHAR(50) | Unique identifier assigned to each product. |
| category | NVARCHAR(50) | The main product category (e.g., Furniture, Technology, Office Supplies). |
| sub_category | NVARCHAR(50) | The product subcategory within the main category. |
| product_name | NVARCHAR(255) | The descriptive name of the product sold. |
| sales | DECIMAL(10,2) | Total revenue generated from the sale of the product. |
| quantity | INT | Number of product units sold in the order. |
| discount | DECIMAL(4,2) | Discount applied to the product sale (expressed as a fraction or percentage). |
| profit | DECIMAL(10,4) | Net profit generated from the sale after costs and discounts. |
