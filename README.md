# Final-Project_AIDI1002 
### By : TejasKumar Patel - 200575242 & Chintan Chauhan - 200564227 
# **Predicting and Mitigating Global Deforestation Using Machine Learning**

---

### **Introduction**

We recognize that deforestation is a critical environmental issue, leading to habitat destruction, biodiversity loss, and increased carbon emissions. Understanding patterns and trends in forest loss is essential for implementing effective conservation measures. In this project, we utilize machine learning techniques, specifically clustering and regression, to analyze global deforestation data and predict future trends.

---

### **Dataset**

We have selected the **Global Forest Change Dataset**, which contains detailed information on deforestation, including:

- **Numerical data:** Tree cover extent, annual forest loss (in hectares), canopy density thresholds, and reforestation data.
- **Categorical data:** Country names, forest types.
- **Temporal data:** Annual forest loss from 2001 to 2022.

This dataset serves as the foundation for analyzing deforestation patterns and predicting future forest loss.

---

### **Objectives**

Our project has the following objectives:
1. To analyze historical deforestation data and identify trends and patterns.
2. To use clustering techniques to group countries based on deforestation rates.
3. To apply regression models to predict future forest loss for specific regions.
4. To recommend conservation strategies to mitigate deforestation in high-risk areas.

---

### **Methodology**

#### **1. Data Preprocessing**
We began by preparing the data for analysis:
- **Data Cleaning:** We handled missing or inconsistent values in forest loss and canopy density fields.
- **Feature Engineering:** We derived metrics like "percentage forest loss" and "rate of change" while incorporating environmental and geographical features.
- **Data Normalization:** Numerical features were normalized to ensure consistency.
- **Data Aggregation:** Deforestation data was aggregated by country and year to facilitate time-series analysis.

#### **2. Clustering**
- **K-Means Clustering:**  
  We used clustering techniques to group countries based on deforestation rates and forest cover data. This helped us identify regions with similar deforestation patterns.
- **Evaluation:**  
  We evaluated the clustering performance using the silhouette score and the elbow method.

#### **3. Regression Analysis**
- **Linear Regression:**  
  We used linear regression to predict future forest loss based on historical trends.
- **Random Forest Regression:**  
  To model complex relationships between deforestation and environmental factors, we applied Random Forest Regression.
- **Validation:**  
  We validated our models using R² score and Mean Absolute Error (MAE).

#### **4. Visualization**
- **Geographical Mapping:**  
  We created interactive maps to highlight deforestation hotspots.
- **Trend Analysis:**  
  Year-by-year forest loss trends were visualized for high-risk regions.
- **Feature Importance:**  
  We identified key drivers of deforestation using SHAP values.

---

### **Recommendations**

1. **Afforestation Programs:**  
   - We propose the implementation of afforestation programs in regions with significant forest loss to restore ecosystems and mitigate climate change.

2. **Policy Reforms:**  
   - We recommend stricter regulations to control illegal logging and agricultural expansion in high-risk zones.

3. **Sustainable Practices:**  
   - We encourage the adoption of sustainable land-use practices to balance development needs with forest conservation.

4. **Awareness Campaigns:**  
   - We believe in promoting awareness about the importance of forests and involving local communities in conservation efforts.

---

### **Conclusion**

We have demonstrated the effectiveness of machine learning techniques in analyzing deforestation trends. By identifying high-risk regions and predicting future forest loss, we have provided actionable insights that can guide conservationists and policymakers. Our project emphasizes the importance of targeted conservation strategies, such as afforestation, stricter policies, and sustainable practices, to combat deforestation and protect global ecosystems.
