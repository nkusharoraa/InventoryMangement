# Advanced Inventory Management

## Project Overview

Effective inventory management is crucial for minimizing costs and ensuring product availability. This project aims to develop and analyze inventory management models, focusing on Economic Order Quantity (EOQ), single-period and multi-period inventory models, and handling stochastic demand.

## Objectives

1. **Data Collection and Preparation**:
   - Gather historical inventory data for a specific product or product category.
   
2. **Inventory Analysis**:
   - Perform exploratory data analysis (EDA) to understand inventory patterns, demand variability, and current management practices.
   
3. **Inventory Models Implementation**:
   - Implement the EOQ model to determine optimal order quantity.
   - Extend the EOQ model to incorporate factors like discounts and variable demand.
   - Implement single-period inventory models to manage perishable or seasonal items.
   - Implement multi-period inventory models to optimize inventory levels over multiple time periods.
   
4. **Model Evaluation**:
   - Evaluate the performance of each model using metrics such as total cost, stockouts, and service levels.
   - Compare the effectiveness of EOQ, single-period, and multi-period models in managing inventory.
   
5. **Forecasting and Visualization**:
   - Generate inventory policies based on model outputs.
   - Visualize the inventory levels, order quantities, and cost implications to assess model accuracy and reliability.
   
6. **Implementation and Documentation**:
   - Implement the selected inventory models using Python, documenting the code, assumptions, and methodology used.
   - Prepare a detailed report summarizing the project, including data insights, model performance, and recommendations for operational decision-making.

## Example
![image](https://github.com/nkusharoraa/SCM/assets/59050030/7e1efab0-726b-4eb1-b6ad-86989de11d55)

```
EOQ: 275.13632984395207
Optimal Order Quantity (Newsvendor Model): 192.26630087873644
Reorder Point: 142.32201101890323, Order Quantity: 275.13632984395207
```

## Visualization Insights for Inventory Management Project

Effective visualization plays a crucial role in understanding inventory patterns, optimizing inventory policies, and making informed decisions. Here are key insights that visualizations can provide in our inventory management project:

### 1. Demand Patterns

Visualizing historical demand data helps in identifying:
- Seasonal trends
- Cyclical patterns
- Irregularities or anomalies in demand

### 2. Economic Order Quantity (EOQ) Calculation

Visualize how EOQ is determined based on:
- Annual demand
- Ordering costs
- Holding costs
<img src="https://github.com/nkusharoraa/SCM/assets/59050030/fc04f7b0-e722-4436-8464-6343520b9c49" width=500 />

### 3. Reorder Points

Illustrate reorder points against actual inventory levels to:
- Determine optimal order times
- Minimize stockouts

### 4. Cost Implications

Plot total costs (holding costs, ordering costs) against order quantities to:
- Optimize inventory management strategies
- Minimize total costs

### 5. Model Performance Comparison

Compare different inventory models (EOQ, single-period, multi-period) by:
- Total cost
- Service levels
- Stockout rates
<img src="https://github.com/nkusharoraa/SCM/assets/59050030/52537f9a-d355-43d0-9fca-e5f4bd36f31e" width=500 />

### 6. Stochastic Demand Analysis

Visualize probabilistic demand scenarios to understand:
- Impact on inventory levels
- Costs associated with demand variability


### 7. Inventory Policy Recommendations

Summarize recommended inventory policies based on model outputs, including:
- Safety stock levels
- Order quantities
- Reorder frequencies

## Skills Utilized

- Inventory management techniques
- Economic Order Quantity (EOQ) model
- Stochastic demand analysis
- Single-period and multi-period inventory models
- Data visualization for inventory patterns and cost implications
- Python programming for data analysis and inventory model implementation

## Potential Impact

- Optimized inventory levels leading to reduced holding and ordering costs.
- Improved service levels and reduced stockouts, enhancing customer satisfaction.
- Data-driven decision-making for inventory policies and procurement strategies.

## Python Code

Here's the Python script to implement inventory management models using EOQ, single-period, and multi-period approaches.

### Prerequisites

Ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`

```bash
pip install pandas numpy matplotlib
