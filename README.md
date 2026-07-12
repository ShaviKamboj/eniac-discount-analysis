# Eniac Discount Analysis 💸

**Is it beneficial for an e-commerce company to discount its products?**
Exploratory data analysis with pandas answering a pricing-strategy question.

📊 [Final presentation (PDF)](Final_Presentation_Group_2.pdf)

## The Business Problem

Eniac, an e-commerce company specializing in tech products, is worried that its aggressive discounting hurts revenue. Management wants a data-driven answer: **should we keep offering discounts, and on which products?**

## Business Questions

- How should products be classified into categories to simplify reporting?
- How are product prices distributed across categories?
- How much revenue do cheap vs. expensive products generate?
- How large are the discounts - absolute and as a percentage of product price - per category?

## Approach

**1. Data cleaning (pandas)**
- Removed duplicate rows
- Fixed corrupted prices (values with two decimal points) using **regex**
- Handled missing values and converted columns to appropriate data types

**2. Feature engineering**
Created four price categories from completed orders:

| Category | Price range |
|---|---|
| Low price | 0 – 100 € |
| Mid price | 101 – 1,000 € |
| High price | 1,001 – 5,000 € |
| High end | > 5,000 € |

**3. Analysis & visualization** — answered each business question with aggregations and charts, then presented a recommendation.

## Tools

`Python` · `pandas` · `matplotlib / seaborn` · `regex` · `Jupyter Notebook`

## Repository Contents

| File | Description |
|---|---|
| `Project_group_file_1.ipynb` | Data cleaning and quality checks |
| `Project_group_file_2.ipynb` | Analysis and business-question answers |
| `Final_Presentation_Group_2.pdf` | Final stakeholder presentation |
