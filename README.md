# D2C Customer Churn Intelligence — Part 2

## Objective

This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis.

The goal is to identify valuable customer groups, churn-risk segments, and retention opportunities.

---

# Methodology

## RFM Features

### Recency
Days since customer's most recent purchase.

### Frequency
Number of purchases made by customer.

### Monetary
Total customer spending.

---

# Additional Behavioral Signals

The segmentation was enhanced using:

- Support ticket activity (`ticket_count`)
- Web engagement (`sessions_30d`)

These signals provide additional customer context beyond traditional RFM analysis.

---

# Customer Segments

The following segments were created:

- Champion
- Loyal Customer
- Potential Loyalist
- At Risk
- Dormant

---

# Key Findings

## Champions
Highest spending and most engaged customers.

## Loyal Customers
Consistent purchasers with strong value.

## Potential Loyalists
Good engagement and growth opportunity.

## At Risk
Customers showing signs of disengagement.

## Dormant
Inactive customers requiring win-back efforts.

---

# Deliverables

| File | Description |
|--------|--------|
| rfm_segmentation.ipynb | Main notebook |
| segments.csv | Customer segmentation output |
| manual_review_cases.csv | Example customers for review |
| retention_strategy.md | Retention recommendations |
| requirements.txt | Python dependencies |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Business Value

The segmentation framework enables:

- targeted retention campaigns
- budget prioritization
- customer lifecycle management
- churn-risk identification

---

# Author

Arjun