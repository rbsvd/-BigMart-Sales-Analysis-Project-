# BigMart Sales Analysis Project

## 🏬 Objective and Scope

### **Objective**  
The goal of this project is to analyze BigMart sales data to uncover insights related to **pricing, outlet type influence, inventory optimization, and sales forecasting**. The project employs machine learning techniques to **predict product sales, optimize inventory levels, and provide strategic recommendations** to enhance profitability.

### **Specific Objectives**  
✔ Understand relationships between **product attributes, outlet characteristics**, and target variables like sales revenue.  
✔ Develop and evaluate **machine learning models** for sales prediction.  
✔ Utilize **clustering** to segment outlets based on sales trends.  
✔ Provide **actionable strategies** for pricing, product placement, and expansion.  

### **Scope**  
🔹 **Exploratory Data Analysis (EDA)**: Identify trends, detect anomalies, and visualize sales patterns.  
🔹 **Data Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical attributes.  
🔹 **Machine Learning Models**: Regression, classification, and clustering to analyze and predict sales performance.  
🔹 **Model Evaluation**: Assess model performance using metrics like RMSE, MAE, and R².  
🔹 **Actionable Insights**: Generate strategic recommendations to improve business decision-making.

---

## 🔬 Methodology

### **Data Preprocessing**  
✔ **Data Cleaning**: Address missing values using mean imputation techniques.  
✔ **Feature Engineering**: Create derived features such as product visibility index and outlet performance ranking.  
✔ **Scaling**: Standardization via **MinMaxScaler** ensures uniform distribution of numerical features.

### **Model Development**  
#### 📊 **Regression Analysis**  
✔ Applied **XGBoost** and **Random Forest Regressor** for **sales prediction**.  
✔ Evaluated performance using RMSE, R², and MAE.

#### 📌 **Classification**  
✔ Categorized outlets into **high-performance, mid-range, and underperforming** using sales thresholds.  
✔ Used **Random Forest Classifier** for precise prediction.

#### 🔍 **Clustering Analysis**  
✔ Implemented **KMeans** to segment outlets into strategic business categories.  
✔ Optimized clustering with **Elbow Method and Silhouette Score**.

#### 🏷 **Sales Impact Analysis**  
✔ Assessed **outlet location type** vs. total sales using barplots.  
✔ Analyzed pricing trends for data-driven pricing optimization.

---

## 📈 Results and Insights

### **Sales Prediction Model Report**  
📌 **Model**: XGBoost Regressor  
🎯 **Objective**: Predict product sales based on outlet type, product visibility, and price.  
📊 **Performance Metrics**:  
✔ **Mean Squared Error (MSE)**: 0.02  
✔ **R-squared (R²)**: 0.89  
✔ **Root Mean Squared Error (RMSE)**: 0.14  
✔ **Mean Absolute Error (MAE)**: 0.07  

**Insights:**  
✔ High prediction accuracy enables **demand forecasting**.  
✔ **Product visibility and outlet type** play significant roles in influencing sales.  

### **Outlet Clustering Report**  
📌 **Model**: KMeans  
🎯 **Objective**: Group outlets based on sales performance for targeted business expansion.  
📊 **Best k**: 3 (Silhouette Score: 0.79)  

✔ **Cluster 1**: High-performance outlets with premium pricing and strong sales.  
✔ **Cluster 2**: Mid-tier outlets with moderate pricing and seasonal demand fluctuations.  
✔ **Cluster 3**: Underperforming outlets that require **strategic pricing improvements**.

---

## 📌 Actionable Recommendations  

### **💰 Pricing Strategy**  
✔ **Dynamic Pricing**: Adjust product prices based on seasonal demand trends.  
✔ **Localized Pricing**: Modify prices to match consumer purchasing behavior across locations.  
✔ **Bundling Offers**: Combine complementary products to increase basket size.  

### **🛒 Product Placement Strategy**  
✔ **High Visibility Zones**: Optimize shelf arrangement based on customer behavior.  
✔ **Aisle Placement**: Place high-selling items at entrance areas to maximize impulse buying.  
✔ **Promotional Endcaps**: Highlight seasonal discounts using strategic display positioning.  

### **🏬 Outlet Expansion Strategy**  
✔ **Invest in High-Sales Locations**: Expand in zones where data suggests strong growth potential.  
✔ **Diversify Outlet Formats**: Introduce compact stores in urban regions while maintaining supermarket chains.  
✔ **Leverage Historical Data**: Use machine learning predictions to optimize new store locations.

---

## 🚀 Environment Setup

### **Prerequisites**  
✔ **Programming Language & Platform**: Python 3.12 & Jupyter Notebook 
✔ **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
