# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means clustering** to segment customers of a retail store based on their purchase behavior. The goal is to group similar customers together, allowing businesses to tailor marketing strategies to specific segments.

---

## 🎯 Objective

Segment customers into distinct groups using unsupervised machine learning, specifically **K-Means Clustering**, based on selected features from their profile and behavior (like income and spending score).

---

## 🧠 Workflow

1. 📥 **Load Dataset**  
   - Read customer data from `Mall_Customers.csv`

2. 🧼 **Preprocess the Data**  
   - Remove unnecessary columns  
   - Handle missing values (if any)  
   - Select relevant features for clustering

3. 📏 **Feature Scaling**  
   - Standardize features using `StandardScaler` for uniform contribution to distance calculations

4. 🧮 **Determine Optimal Clusters**  
   - Use the **Elbow Method** to find the best `k` value by plotting Within-Cluster Sum of Squares (WCSS)

5. 🌀 **Apply K-Means Clustering**  
   - Fit the model with the optimal number of clusters  
   - Predict the cluster for each customer

6. 📊 **Visualize the Clusters**  
   - Use scatter plots to visualize groupings in 2D space (e.g., Annual Income vs. Spending Score)

---

## 🗃️ Dataset

- **Name**: Mall Customers Dataset  
- **Format**: CSV  
- **Features**:
  - `CustomerID`  
  - `Gender`  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`

---

## 🛠️ Installation

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
Place Mall_Customers.csv in the root or update the path in the notebook/script.

Run the notebook:

bash
Copy code
jupyter notebook Prodigy_ML_02.ipynb
📈 Sample Output
💡 Elbow Method Plot: To select the ideal number of clusters

🧠 Customer Clusters: Shown using scatter plot with different colors

📊 Interpretation: Clusters may indicate high spenders, low income, young shoppers, etc.

🔮 Future Enhancements
✨ Add dimensionality reduction (PCA or t-SNE) for better visualization

📊 Perform deeper feature engineering (e.g., RFM analysis)

🤖 Try other clustering methods (DBSCAN, Agglomerative)

🌐 Deploy with a dashboard for business users

👨‍💻 Author
Made with ❤️ by MAULI
📬 Reach me at [maulikangude007@gmail.com]


