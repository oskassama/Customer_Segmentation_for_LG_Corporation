# Customer Segmentation Analysis for LG Corporation

A comprehensive customer segmentation analysis using K-Means clustering and RFM (Recency, Frequency, Monetary) analysis to identify distinct customer groups and provide actionable business insights.

## 📊 Project Overview

This project performs advanced customer segmentation to help LG Corporation understand their customer base and develop targeted marketing strategies. The analysis combines traditional statistical methods with machine learning techniques to create meaningful customer segments.

## 🎯 Key Features

- **Exploratory Data Analysis (EDA)** - Comprehensive data exploration and visualization
- **K-Means Clustering** - Unsupervised machine learning for customer grouping
- **RFM Analysis** - Recency, Frequency, Monetary value segmentation
- **Customer Lifetime Value (CLV)** calculation
- **Interactive Dashboards** - Plotly visualizations for business insights
- **Model Deployment Ready** - Saved models and prediction functions

## 📁 Data Fields

The analysis uses the following customer attributes:
- **Demographics**: Age, Gender
- **Financial**: Income, Spending Score
- **Behavioral**: Purchase Frequency, Last Purchase Amount, Membership Years
- **Preferences**: Preferred Category

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Machine Learning**: scikit-learn
- **Model Persistence**: joblib

## 📈 Customer Segments Identified

### K-Means Clusters (4 segments)
- Cluster 0-3: Data-driven segments based on behavioral patterns

### RFM Segments (9 categories)
- **Champions**: Best customers - high value, frequent purchases
- **Loyal Customers**: Regular buyers with good value
- **Potential Loyalists**: Recent customers with growth potential
- **New Customers**: Recent first-time buyers
- **Promising**: Customers with potential for growth
- **Cannot Lose Them**: High-value customers at risk
- **At Risk**: Previously good customers showing decline
- **Price Sensitive**: Customers focused on deals and discounts
- **Others**: Customers needing re-engagement

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

### Running the Analysis
1. Place your customer data CSV file in the project directory
2. Update the file path in the script: `df = pd.read_csv('your_data_file.csv')`
3. Run the analysis:
```bash
python customer_segmentation_analysis.py
```

## 📊 Key Outputs

### Generated Files
- `customer_segmentation_scaler.pkl` - Preprocessing scaler
- `customer_segmentation_kmeans.pkl` - Trained K-means model
- `customer_segmentation_results.csv` - Analysis results with segments

### Visualizations
- Customer distribution charts
- Correlation matrices
- Cluster visualization plots
- RFM segment analysis
- Interactive dashboards

## 💡 Business Insights

The analysis provides actionable insights including:
- Customer segment characteristics and sizes
- Revenue contribution by segment
- Targeted marketing recommendations
- Customer lifetime value analysis
- Retention strategies by segment

## 🔧 Model Deployment

The project includes a prediction function for real-time customer segmentation:

```python
prediction = predict_customer_segment(
    age=35, 
    income=75000, 
    spending_score=65, 
    membership_years=4, 
    purchase_frequency=25, 
    last_purchase_amount=350
)
```

## 📋 Strategic Recommendations

Each customer segment comes with specific business recommendations:
- **Champions**: Reward and retain through VIP programs
- **Loyal Customers**: Upsell premium products and services
- **At Risk**: Re-engagement campaigns and personalized offers
- **New Customers**: Onboarding programs and relationship building

## 🔍 Analysis Highlights

- **Optimal Clusters**: Determined using Elbow method and Silhouette analysis
- **Feature Engineering**: Age groups, income brackets, spending categories
- **Statistical Validation**: Correlation analysis and distribution testing
- **Business Metrics**: CLV calculation and segment profitability

## 🤝 Contributing

This project was developed as a Business Analytics Capstone final project. Contributions and improvements are welcome.

---
