
# 🛍️ Customer Segmentation using K-means Clustering

This project implements **K-means Clustering** on the Mall Customer dataset to segment customers based on their **Annual Income** and **Spending Score**. The aim is to help businesses understand customer behavior and tailor marketing strategies accordingly.

[![LinkedIn Post](https://img.shields.io/badge/View_on-LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/posts/sumansekhar-sahoo_machinelearning-customersegmentation-kmeans-activity-7338602168653881344-PvtE?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFbWbFkBBD_ckmIB0-Z1ZAk25yadMwBisI0)

---

## 📁 Dataset

- **Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **File**: `Mall_Customers.csv`
- **Features Used**:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 📊 Objective

To segment customers into distinct groups using **unsupervised learning** (K-means) based on purchasing behavior and income levels.

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- StandardScaler
- KMeans Clustering

---

## 🚀 How to Run

1. Clone the repository:

   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
`

2. Install dependencies:

   
   pip install -r requirements.txt
  

3. Run the script:

   
   python kmeans_customer_segmentation.py
   

4. Output:

   * Visualizes clusters
   * Saves `Customer_Segments.csv` with assigned cluster labels

---

## 📌 Key Steps

* Load and explore the dataset
* Select and scale relevant features
* Use the **Elbow Method** to find optimal `k`
* Apply **KMeans** for clustering
* Visualize segmented customer groups
* Analyze each cluster's average income and spending behavior

---

## 📸 Output Visualization

![Figure_1](https://github.com/user-attachments/assets/5c7e56c9-deb3-4a12-ab93-c118cfe9f9a1)
![Figure_2](https://github.com/user-attachments/assets/13c4e571-d591-4390-ad00-7c81c55b7590)


> 📍 Customers are clearly divided into distinct groups, helping businesses target the right customers with personalized strategies.

---

## 📈 Sample Cluster Analysis

| Cluster | Avg Income (k\$) | Avg Spending Score |
| ------- | ---------------- | ------------------ |
| 0       | 88.0             | 17.0               |
| 1       | 25.0             | 80.0               |
| 2       | 55.0             | 50.0               |
| 3       | 30.0             | 20.0               |
| 4       | 90.0             | 85.0               |

---

## 📬 Connect with Me

* 💼 [LinkedIn – Suman Sekhar Sahoo](https://www.linkedin.com/in/sumansekhar-sahoo/)
* 📫 Email: [sumansekhar.sahoo25@gmail.com](mailto:sumansekhar.sahoo25@gmail.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).





