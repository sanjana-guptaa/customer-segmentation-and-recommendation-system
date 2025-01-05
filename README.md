# Customer Segmentation and Recommendation System

This project demonstrates the development of a **Customer Segmentation and Recommendation System** using advanced data cleaning, preprocessing, feature engineering, and clustering techniques. It analyzes customer transactional data to provide meaningful insights and personalized recommendations.

## **Project Features**
- **Data Cleaning & Preprocessing**: Handling missing values, duplicates, anomalies, and outliers.
- **Feature Engineering**:
  - **RFM metrics**: Recency, Frequency, and Monetary value.
  - **Behavioral features**: Shopping patterns like favorite days/hours, and time between purchases.
  - **Geographic insights** and cancellation trends.
- **Dimensionality Reduction**: Utilizing PCA to address multicollinearity and reduce dimensionality.
- **Clustering**: Applying K-means to segment customers based on purchasing behavior.
- **Visualization**: Comprehensive insights with visualizations for key metrics and patterns.

## **Dataset Description**
The dataset contains transactional data with the following columns:
- **`InvoiceNo`**: Transaction identifier.
- **`StockCode`**: Product code.
- **`Description`**: Product description.
- **`Quantity`**: Number of items purchased.
- **`InvoiceDate`**: Date and time of the transaction.
- **`UnitPrice`**: Price per item.
- **`CustomerID`**: Unique customer identifier.
- **`Country`**: Customer's country.

### **Engineered Features**
- **RFM Metrics**: Recency, Frequency, and Monetary value.
- **Behavioral Insights**: Shopping frequency, favorite times, and product diversity.
- **Geographic Patterns**: Country of purchase and regional trends.
- **Cancellation Metrics**: Frequency and rate of cancellations.
- **Spending Trends**: Monthly spending patterns and spending trends.

## **Methodology**
1. **Data Cleaning**:
   - Address missing and duplicate values.
   - Handle cancelled transactions and anomalous stock codes.
   - Treat outliers and normalize data.
2. **Feature Engineering**:
   - Construct customer-centric features.
   - Analyze patterns for insights.
3. **Dimensionality Reduction**:
   - Apply PCA to simplify data while retaining variance.
4. **Clustering**:
   - Implement K-means clustering to identify customer segments.

## **Tools and Libraries**
- **Data Analysis**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`.
- **Feature Engineering**: `scikit-learn`, `scipy`.
- **Clustering**: `KMeans`, `Yellowbrick`.
- **Visualization**: `matplotlib`, `plotly`, `seaborn`.

## **Results and Insights**
- Customer segments created based on spending behavior, purchase diversity, and geographical trends.
- Identification of high-value customers, frequent shoppers, and region-based patterns.
- Recommendations tailored to customer segments.
