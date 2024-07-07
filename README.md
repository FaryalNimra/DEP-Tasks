# DEP-Task1
# 🛒 Customer Segmentation for a Retail Store

## 📋 Project Overview

This project aims to segment customers based on their purchasing behavior using transaction data. By analyzing historical sales data, we identify distinct customer groups to aid in targeted marketing strategies, personalized promotions, and improving customer retention.

## 📂 Dataset

The dataset includes the following columns:
- `CustomerID`
- `Gender`
- `Location`
- `Tenure_Months`
- `Transaction_ID`
- `Transaction_Date`
- `Product_SKU`
- `Product_Description`
- `Product_Category`
- `Quantity`
- `Avg_Price`
- `Delivery_Charges`
- `Coupon_Status`
- `GST`
- `Date`
- `Offline_Spend`
- `Online_Spend`
- `Month`
- `Coupon_Code`
- `Discount_pct`

## 🛠️ Steps Performed

### 1. Data Cleaning and Preprocessing
- Handle missing values using mean imputation.
- Select relevant features for analysis.

### 2. Exploratory Data Analysis (EDA)
- Generate visualizations to understand data distribution and relationships.
  - Scatter plots
  - Histograms
  - Box plots
  - Heatmaps

### 3. K-means Clustering
- Standardize the data to ensure equal contribution of all features.
- Determine the optimal number of clusters using the Elbow Method.
- Apply K-means clustering to segment customers.

### 4. Visualization of Customer Segments
- Visualize clusters using scatter plots to understand the segmentation.

## 📊 Visualizations

### Scatter Plot of Online Spend vs Offline Spend by Gender

### Distribution of Average Price

### Correlation Matrix Heatmap

### Customer Segments (K-means Clusters)

## 📈 Key Insights
- Customers are segmented based on their spending behavior across online and offline channels.
- Clusters help identify distinct groups for targeted marketing and promotions.

## 🛠️ How to Run the Code

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/retail-customer-segmentation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd retail-customer-segmentation
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook or Python script to perform the analysis:
    ```bash
    jupyter notebook customer_segmentation.ipynb
    ```
   OR
    ```bash
    python customer_segmentation.py
    ```

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*Happy Analyzing!*

