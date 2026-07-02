# Country Clustering for Socio-Economic Analysis using K-Means

An unsupervised machine learning project aimed at categorizing countries based on global socio-economic and public health factors. This data-driven analysis helps non-governmental organizations (NGOs) and international bodies identify nations that require the most immediate developmental aid and strategic fund allocation.

## 📌 Project Overview
Efficient distribution of international resources is a critical challenge. This pipeline uses **K-Means Clustering** to group nations based on human health and economic health features, isolating distinct patterns between developed, developing, and underdeveloped economies.

The project handles the complete analytical loop: from Exploratory Data Analysis (EDA) and outlier analysis to model profiling and dynamic geographical visualizations.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (K-Means, PCA, StandardScaler)
- **Data Visualization:** Matplotlib, Seaborn
- **Geospatial Mapping:** Plotly (Choropleth Maps)

## 📊 Methodology & Key Steps

1. **Exploratory Data Analysis (EDA):** Investigated data distributions, inter-feature correlations (e.g., GDP vs. Child Mortality), and flagged skewed distributions.
2. **Feature Scaling:** Applied `StandardScaler` to uniformize varying dimensions across currency, mortality rates, and percentages.
3. **Hyperparameter Tuning:** Evaluated the optimal number of clusters ($K$) using both the **Elbow Method (Inertia)** and **Silhouette Score analysis**.
4. **Dimensionality Reduction:** Utilized **PCA (Principal Component Analysis)** to reduce data into a 2D plane for crisp visual cluster segregation.
5. **Interactive Geo-Mapping:** Leveraged **Plotly Express** to output global interactive world maps representing clustered development tiers.

## 📁 Repository Structure
```text
├── Country-data.csv       # Global socio-economic dataset
├── Country_KMeans.ipynb       # Core Jupyter Notebook with full implementation
├── Country_KMeans.html        # Exported interactive notebook run preview
└── README.md                  # Project documentation & insights
