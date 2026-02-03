# 🛍️ Mall Customer Segmentation - Unsupervised Learning Project

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/ML-Unsupervised-orange.svg)
![Clustering](https://img.shields.io/badge/Clustering-K--Means%20%7C%20DBSCAN-green.svg)

An unsupervised machine learning project to segment mall customers into distinct groups for targeted marketing strategies.

## 🎯 Project Overview

This project uses clustering algorithms to identify customer segments based on:
- Age
- Annual Income
- Spending Score

**Key Achievement:** Successfully identified 5 distinct customer segments with actionable marketing strategies.

---

## 📊 Dataset

- **Source:** Mall Customer Segmentation Dataset
- **Size:** 200 customers
- **Features:** 5 (CustomerID, Gender, Age, Annual Income, Spending Score)
- **Type:** Numerical + Categorical

---

## 🛠️ Technologies Used

**Core Libraries:**
- Python 3.8+
- pandas, numpy - Data manipulation
- matplotlib, seaborn - Visualization
- scikit-learn - Machine learning

**Algorithms Implemented:**
- K-Means Clustering
- DBSCAN (Density-based clustering)
- PCA (Principal Component Analysis)

---

## 🔍 Methodology

### 1. Exploratory Data Analysis (EDA)
- Univariate analysis (Age, Income, Spending distributions)
- Bivariate analysis (Income vs Spending patterns)
- Correlation analysis
- Gender-based segmentation

### 2. K-Means Clustering
- **Elbow Method:** Optimal K = 5
- **Silhouette Analysis:** Best score = {score}
- **Clusters Identified:** 5 distinct segments
- **Validation:** Multiple metrics used

### 3. DBSCAN Clustering
- **Parameters:** eps=0.7, min_samples=5
- **Outlier Detection:** {n_noise} outliers identified
- **Comparison:** Validated K-Means results

### 4. Dimensionality Reduction (PCA)
- Reduced 3D data to 2D
- Variance Explained: {variance}%
- Enhanced visualization

---

## 📈 Results

### Customer Segments Identified:


                    Count  Avg_Age  Avg_Income  Avg_Spending Gender_Split
Cluster_Name                                                             
Budget Conscious       23     45.2        26.3          20.9     M:9 F:14
High Rollers           39     32.7        86.5          82.1    M:18 F:21
Potential Targets      35     41.1        88.2          17.1    M:19 F:16
Standard Customers     81     42.7        55.3          49.5    M:33 F:48
Young Spenders         22     25.3        25.7          79.4     M:9 F:13


### Key Findings:
✅ Clear segmentation patterns identified  
✅ Income vs Spending shows 5 distinct groups  
✅ DBSCAN detected {n_noise} outlier customers  
✅ PCA successfully visualized multi-dimensional data  
✅ Actionable marketing strategies developed  

---

## 💡 Business Impact

**Marketing Strategies:**

**Budget Conscious (Low Income, Low Spending):**
- Focus on discounts and value propositions
- Loyalty programs
- Budget product lines

**Young Spenders (Low Income, High Spending):**
- Social media marketing
- Trendy products
- Installment options

**High Rollers (High Income, High Spending):**
- VIP treatment
- Premium products
- Exclusive offers

**Potential Targets (High Income, Low Spending):**
- Quality-focused messaging
- Educational content
- Investment products

---

## 📁 Project Structure
```
customer-segmentation/
│
├── customer_segmentation_analysis.py    # Main analysis script
├── kmeans_model.pkl                     # Trained K-Means model
├── scaler.pkl                           # Feature scaler
├── pca_model.pkl                        # PCA model
├── Customer_Segmentation_Results.csv    # Final results
├── requirements.txt                     # Dependencies
└── README.md                            # Documentation
```

---

## 🚀 How to Run

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```

### Installation
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/customer-segmentation.git
cd customer-segmentation

# Install dependencies
pip install -r requirements.txt

# Run analysis
python customer_segmentation_analysis.py
```

---

## 📊 Visualizations

The project includes:
- Age, Income, Spending distributions
- Income vs Spending scatter plots
- Correlation heatmaps
- Elbow curve (K-Means)
- Silhouette analysis
- Cluster visualizations
- PCA 2D projections
- Algorithm comparison plots

---

## 🎓 Key Learnings

**Technical Skills:**
- Unsupervised learning algorithms
- Elbow method for optimal K
- Silhouette score validation
- DBSCAN parameter tuning
- PCA for dimensionality reduction
- Outlier detection techniques

**Business Skills:**
- Customer segmentation
- Marketing strategy development
- Data-driven decision making
- Cluster interpretation

---

## 🔮 Future Improvements

1. **Hierarchical Clustering:** Compare with agglomerative methods
2. **More Features:** Include purchase history, visit frequency
3. **Time Series:** Analyze seasonal patterns
4. **Predictive Model:** Predict cluster for new customers
5. **A/B Testing:** Validate marketing strategies

---

## 👤 Author

**Essa**
- Project Duration: February 2026
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

---

## 🙏 Acknowledgments

- Mentor: Abdullah
- Dataset: Mall Customer Segmentation (Kaggle)
- Inspiration: Real-world retail analytics

---

## 📝 License

This project is open source and available under the MIT License.

---

**Built with 🧠 using Unsupervised Machine Learning**
