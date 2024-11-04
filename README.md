# Customer Segmentation Analysis using RFM Approach

## Overview
This project focuses on analyzing customer behavior and segmenting customers using the RFM (Recency, Frequency, Monetary) approach. By analyzing various customer attributes and transaction data, we aim to help businesses optimize their marketing strategies, improve customer service, and reduce customer churn.

## Business Problem
Businesses need to understand their customers better to:
- Optimize marketing campaigns
- Improve customer retention
- Increase profitability
- Enhance customer service
- Prevent customer churn

## Dataset
The dataset contains comprehensive customer information including:
- Customer demographics (ID, name, email, phone, address, age, gender, income)
- Transaction details (purchase dates, amounts, products)
- Product information (category, brand, type)
- Order information (shipping method, payment method, status)
- Customer feedback

## Project Structure
```
├── data/
│   └── customer_data.csv
├── notebooks/
│   └── customer_segmentation_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   └── rfm_analysis.py
├── README.md
└── requirements.txt
```

## Methodology

### 1. Data Exploration and Analysis
- Demographic analysis
- Transaction patterns
- Product preferences
- Payment and shipping analysis
- Temporal analysis
- Customer feedback analysis

### 2. RFM Analysis Implementation
- **Recency**: Time since customer's last purchase
- **Frequency**: Number of purchases
- **Monetary**: Total spending amount

### 3. Customer Segmentation
Using K-means clustering, customers are segmented into three tiers:
- **Gold/Top-tier**: High frequency, high monetary value, low recency
- **Silver/Middle-tier**: Moderate across all metrics
- **Bronze/Last-tier**: Low frequency, low monetary value, high recency

## Key Findings

### Demographic Insights
- Majority of transactions from US
- Higher male customer representation
- Medium income customers form the largest segment
- Younger customer base (majority below 30)

### Transaction Patterns
- Electronics is the most popular category
- 14% negative feedback rate
- Credit/debit cards are preferred payment methods
- Equal distribution across shipping methods
- 16% orders in pending status

### Seasonal Trends
- Peak transactions in April and August
- Consistent weekly distribution with slight Thursday preference

## Recommendations

### For Business Growth
1. **Top-tier Customer Retention**
   - Implement exclusive rewards
   - Provide premium services
   - Early access to new products/features

2. **Middle-tier Customer Development**
   - Targeted promotions
   - Loyalty program benefits
   - Personalized communication

3. **Bronze-tier Customer Engagement**
   - Analysis of spending patterns
   - Targeted marketing campaigns
   - Special onboarding offers

### Operational Improvements
1. **Order Management**
   - Address pending order issues
   - Improve delivery times
   - Enhanced order tracking

2. **Product Strategy**
   - Focus on electronics category
   - Optimize brand portfolio
   - Review pricing strategies

## Technical Implementation

### Requirements
```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

### Setup
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter notebook: `jupyter notebook`

## Future Work
- Implement predictive modeling for customer churn
- Develop real-time customer scoring system
- Integration with CRM systems
- Enhanced visualization dashboard
- Customer lifetime value prediction

## Contributors
[Your Name/Team]

## License
[License Type]
