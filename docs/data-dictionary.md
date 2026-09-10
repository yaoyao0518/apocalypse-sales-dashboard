# Data Dictionary

## Apocolypse Store

| Field | Type | Description |
|---|---|---|
| Product ID | Integer | Unique product identifier |
| Product Name | Text | Name of the survival product |
| Price | Decimal | Selling price in USD |
| Production Cost | Decimal | Cost to produce one unit in USD |

## Apocolypse Sales

| Field | Type | Description |
|---|---|---|
| Cust ID | Integer | Customer identifier |
| Customer | Text | Customer name |
| Product ID | Integer | Product identifier |
| Order ID | Integer | Unique order identifier |
| Units Sold | Integer | Number of units sold in the order |
| Date Purchased | Date | Date the order was placed |

## Customer Information

| Field | Type | Description |
|---|---|---|
| Customer ID | Integer | Unique customer identifier |
| Customer | Text | Customer name |
| Address | Text | Street address |
| City | Text | City |
| State | Text | State abbreviation |
| Zipcode | Integer | Postal code |

## Customer Buyer Information

| Field | Type | Description |
|---|---|---|
| Buyer ID | Integer | Unique buyer identifier |
| Product ID Purchased | Integer | Product identifier |
| Total Purchased | Integer | Total units purchased |
| State | Text | State abbreviation |
| Age | Integer | Buyer age |
| Customer ID | Integer | Customer identifier |
