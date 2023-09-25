# 💸 Customer Spend-O-Meter 💸

Peek into the spending habits of your customers with the `Customer Spend-O-Meter`! Dive deep into your datasets and figure out who's splurging and who's saving. Built for businesses with an eye on customer trends!

## What's the Magic?

This script whirls through your customer order data and churns out the total spend for each customer. Want to know who's your top spender or who's been budget-conscious? You're just a script away!

## Features

- **Swift Data Processing**: Powered by PySpark, this script guarantees a quick and efficient analysis.
- **Precise Calculations**: Rounds off customer spending to the nearest cent for accurate insights.
- **Instant Insights**: The script offers a peek into the top 10 customers based on their spending.

## Tools at Play

- **PySpark**: The engine driving the script's fast data processing.

## Setup & Run

1. PySpark must be summoned! If you haven't already:
```
pip install pyspark
```

2. Point to your data:
Make sure to modify the path in the script (`file:///SparkCourse/customer-orders.csv`) to your actual data file location.

3. Ignite the Spend-O-Meter:
```
python customer_spend_insights.py
```

## Sneak Peek at the Output

The Spend-O-Meter will display something akin to:

```
+-----------+-----------+
|customer_id|total_spent|
+-----------+-----------+
|       1234|     100.12|
|       5678|     200.34|
...
+-----------+-----------+
```

## 🛍️ Unleash the power of insights and drive your business strategies! 🚀
