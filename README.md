# Customer-Segmentation-using-K-Means-Mall-Customers-Dataset-
This project focuses on Customer Segmentation using the famous Mall Customers Dataset from Kaggle.
The goal is to group mall customers into distinct clusters based on their Annual Income and Spending Score, so businesses can better understand customer behavior and target marketing strategies effectively.

By clustering customers, businesses can better understand their audience and design **personalized marketing strategies**.

---

## 📂 Dataset
- **Source:** [Mall Customer Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Attributes:**
  - `CustomerID` → Unique identifier
  - `Gender` → Male/Female
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## ⚙️ Tech Stack
- **Python**
- **Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

Steps Covered
1. 📥 Data Import & Exploration

Loaded dataset using pandas

Checked data types, null values, and basic statistics

2. 📊 Data Preprocessing

Selected key features (Income & Spending Score)

Applied StandardScaler to normalize data

3. 🔍 Determining Optimal Clusters

Used Elbow Method to determine best number of clusters (k)

4. 🤖 K-Means Clustering

Applied KMeans algorithm

Segmented customers into distinct groups

5. 🎨 Visualization

Plotted clusters with scatter plots

Visualized centroids for each cluster

6. 📈 Cluster Analysis

Analyzed average spending per cluster

Labeled clusters as High Spenders, Low Spenders, Medium Spenders, etc.

🎁 Bonus Work

Implemented DBSCAN clustering for comparison

Compared results with K-Means to analyze effectiveness

📌 Results & Insights

Customers were successfully segmented into 5 meaningful groups.

Example findings:

Cluster 1: High income, low spending → "Careful Customers"

Cluster 2: Low income, high spending → "Impulsive Customers"

Cluster 3: Average income, average spending → "Standard Customers"

Cluster 4: High income, high spending → "Target Customers"

Cluster 5: Low income, low spending → "Cautious Customers"

📷 Sample Visualization
Scikit-learn → Scaling & Clustering
