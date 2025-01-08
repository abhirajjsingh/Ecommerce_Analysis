# E-commerce Returns Analysis Assessment

## Background
You are given a dataset containing e-commerce transactions and returns data. Your task is to analyze patterns in product returns and identify potential anomalies.

## Assignment Tasks (Time limit: 2 hours)

### 1. Data Analysis (40%)
- Load and clean the provided datasets
- Perform exploratory data analysis:
  - Calculate basic statistics for returns by product category
  - Analyze the distribution of return reasons
  - Find the average time between purchase and return
- Create at least 2 visualizations showing key patterns in the data

### 2. Anomaly Detection (60%)
- Identify products with unusually high return rates
- Find customers with abnormal return behavior
- Use any statistical method of your choice to detect outliers
- Create a visualization showing the anomalies you detected

## Deliverables
1. Jupyter notebook containing your analysis with clear comments
2. Brief summary (max 1 page) explaining your findings

## Evaluation Criteria
- Code quality and organization (30%)
- Technical analysis and methodology (40%)
- Data visualization (20%)
- Documentation and explanation (10%)

## Dataset Description

1. `transactions.csv`:
   - transaction_id
   - customer_id
   - product_id
   - order_date
   - delivery_date
   - price
   - category
   - merchant_id

2. `returns.csv`:
   - transaction_id
   - return_date
   - return_reason
   - product_condition
   - refund_amount

