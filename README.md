# Customer Segmentation using Machine Learning

## 📌 Project Overview
Customer Segmentation is an important application of Machine Learning used by businesses to understand customer behavior and improve marketing strategies.  

This project uses the **K-Means Clustering Algorithm** to group customers into different segments based on their:
- Annual Income
- Spending Score

The project also includes an interactive **Gradio Web Interface** for real-time customer segment prediction.

---

# 🎯 Objectives
- Analyze customer purchasing behavior
- Group customers into meaningful clusters
- Identify high-value customers
- Improve business decision-making using data analysis

---

# 📊 Dataset Information
The dataset used in this project is the **Mall Customers Dataset**.

## Features Used
| Feature | Description |
|---|---|
| Annual Income (k$) | Customer yearly income |
| Spending Score (1-100) | Customer spending behavior score |

---

# ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Gradio

---

# 🧠 Machine Learning Algorithm
## K-Means Clustering
K-Means is an unsupervised machine learning algorithm used to divide data into clusters based on similarity.

### Why K-Means?
- Simple and efficient
- Works well for customer segmentation
- Helps identify customer groups visually

---

# 🔄 Project Workflow
1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Elbow Method for optimal clusters
5. K-Means Model Training
6. Cluster Visualization
7. Gradio Interface Deployment

---

# 📈 Data Visualization
The project visualizes customer groups using scatter plots based on:
- Annual Income
- Spending Score

Different colors represent different customer segments.

---

# 🌐 Gradio Web Application
The project includes a Gradio-based interactive web application where users can:
- Enter customer income
- Enter spending score
- Predict customer cluster instantly

---

# 📌 Output
The system predicts the cluster/category to which the customer belongs.

Example:
```text
Customer belongs to Cluster 2
