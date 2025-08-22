# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers based on purchasing behavior and demographics.  
Customer segmentation helps businesses understand their customer base, improve marketing strategies, and deliver personalized services.

---

## 📌 Project Overview
The main goal of this project is to:
- Analyze customer data.
- Apply **K-Means Clustering** to identify distinct customer groups.
- Visualize clusters to understand customer behavior patterns.
- Provide business insights for targeted marketing.

---

## 📊 Dataset
The project uses a **customer dataset** with the following features:
- **CustomerID**: Unique customer identifier  
- **Gender**: Male / Female  
- **Age**: Customer age  
- **Annual Income (k$)**: Customer income in thousands  
- **Spending Score (1-100)**: Score assigned based on spending patterns  

> Dataset Example:
| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|-------------------------|
| 0001       | Male   | 19  | 15                 | 39                      |
| 0002       | Male   | 21  | 15                 | 81                      |
| 0003       | Female | 20  | 16                 | 6                       |

---

## ⚙️ Technologies Used
- **Python 3.x**
- **Libraries**:
  - `pandas` – data manipulation
  - `numpy` – numerical computations
  - `matplotlib` & `seaborn` – data visualization
  - `scikit-learn` – machine learning (K-Means clustering, scaling, evaluation)

---

## 🔑 Key Steps
1. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Normalize/scale features  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots (age, income, spending score)  
   - Pair plots to explore feature relationships  

3. **K-Means Clustering**  
   - Apply the **Elbow Method** to find optimal number of clusters (k).  
   - Train K-Means model and assign cluster labels.  

4. **Visualization of Clusters**  
   - Plot customer segments in 2D space using income & spending score.  
   - Use colors to represent different clusters.  

---

## 📈 Results
- Customers are grouped into **distinct clusters** such as:
  - **High Income, High Spend (Premium Customers)**  
  - **Low Income, Low Spend (Budget Customers)**  
  - **Young Shoppers**  
  - **Older Low Spenders**  

- These insights can help businesses **personalize marketing campaigns** and **improve retention strategies**.

---

