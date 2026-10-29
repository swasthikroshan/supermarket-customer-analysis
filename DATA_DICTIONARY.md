# Data Dictionary — Supermarket Customer & Sales Analysis

## Dataset Overview

- **Dataset:** Supermarket Customer and Sales Dataset
- **Records:** 100 transactions
- **Columns:** 11
- **Currency:** Indian Rupees (INR)
- **Format:** CSV

## Column Definitions

| Column | Description | Data Type |
|---|---|---|
| Transaction_ID | Unique identifier for each transaction | Text |
| Date | Date the transaction occurred | Date |
| Customer_ID | Identifier assigned to a customer | Text |
| Gender | Customer's recorded gender or preference not to say | Category |
| Age | Customer's age in years | Integer |
| Product_Category | Category of products purchased | Category |
| Quantity | Number of units purchased | Integer |
| Unit_Price_INR | Price per unit in Indian Rupees | Numeric |
| Total_Amount_INR | Total transaction amount in Indian Rupees | Numeric |
| Payment_Method | Payment method used: UPI, Cash, or Card | Category |
| City | City associated with the transaction | Category |

## Data Quality Notes

- Transaction IDs and customer IDs are identifiers, not quantities.
- Dates should be stored consistently in date format.
- Revenue calculations should use `Total_Amount_INR`.
- Check for missing values, duplicate transaction IDs, and inconsistent category labels before analysis.
- Customer IDs are pseudonymous identifiers; avoid adding personal identifying information.

## Intended Use

This dataset supports sales performance analysis, product category comparisons, customer spending analysis, and payment method evaluation using spreadsheet tools and visualizations.
