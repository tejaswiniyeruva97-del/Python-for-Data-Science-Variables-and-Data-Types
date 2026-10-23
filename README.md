# Python-for-Data-Science-Variables-and-Data-Types
## Project Overview
The Sales Data Calculator is a Python project used to analyze sales values and calculate basic sales statistics.

## Objective
To understand basic numerical data analysis using Python.

## Tools Used
- Python
- Jupyter Notebook

## Features
- Calculate total sales
- Calculate average sales
- Find the highest sale
- Find the lowest sale

## Python Code
```python
sales = [1200, 2500, 1800, 3200, 1500, 4000, 2800]

total_sales = sum(sales)
average_sales = total_sales / len(sales)
highest_sale = max(sales)
lowest_sale = min(sales)

print("Total Sales:", total_sales)
print(f"Average Sales: {average_sales:.2f}")
print("Highest Sale:", highest_sale)
print("Lowest Sale:", lowest_sale)
```

## Expected Output
```text
Total Sales: 17000
Average Sales: 2428.57
Highest Sale: 4000
Lowest Sale: 1200
```

## Functions Used
- `sum()` - Calculates total sales.
- `len()` - Counts the number of sales values.
- `max()` - Finds the highest sale.
- `min()` - Finds the lowest sale.

## Results and Analysis
The total sales are 17000.
The average sales are 2428.57.
The highest sale is 4000.
The lowest sale is 1200.

## Conclusion
This project demonstrates how Python can analyze sales data quickly and accurately.
