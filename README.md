# 💳 Credit Card Customer Segmentation

Customer segmentation using K-Means and Hierarchical Clustering to identify distinct customer groups and generate actionable business insights for targeted marketing and customer retention.

---

## 📌 Project Overview

Financial institutions manage customers with diverse spending habits, credit limits, and interaction preferences. Understanding these behavioral differences helps businesses improve marketing strategies, customer engagement, and resource allocation.

This project applies unsupervised machine learning techniques to segment customers into meaningful groups based on their credit card usage and banking behavior.

---

## 🎯 Business Problem

A credit card company wants to:

- Identify high-value customers
- Improve targeted marketing campaigns
- Increase customer retention
- Reduce servicing costs
- Personalize products and offers

Instead of treating every customer the same, clustering techniques help group customers with similar behaviors.

---

## 📂 Dataset

The dataset contains customer information such as:

- Average Credit Limit
- Total Credit Cards
- Bank Visits
- Online Visits
- Customer Service Calls

Additional features were engineered to improve clustering performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

Performed:

- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Pairplots
- Distribution Analysis
- Outlier Detection

---

## ⚙️ Data Preprocessing

- Missing value check
- Outlier treatment (Winsorization)
- Feature Engineering
- Standard Scaling

Engineered Features:

- Credit Utilization
- Bank Interaction

---

## 🤖 Machine Learning Techniques

### K-Means Clustering

- Elbow Method for optimal K
- Silhouette Score evaluation
- Cluster Profiling

### Hierarchical Clustering

Tested multiple linkage methods:

- Single
- Complete
- Average
- Ward

Compared clusters using Cophenetic Correlation.

---

## 📈 Results

Three major customer segments were identified.

### 1. Elite Digital Users

- High credit limits
- Multiple credit cards
- Heavy online usage
- High-value customers

### 2. Mass Market Moderates

- Moderate credit usage
- Balanced interaction channels
- Largest customer segment

### 3. Offline Dependent Customers

- Low credit limits
- Frequent bank visits
- High customer support usage

Hierarchical clustering also revealed a small group of Dormant Elite customers with high credit limits but very low activity.

---

## 💡 Business Recommendations

- Offer premium cards and travel benefits to Elite Digital Users.
- Promote cashback and loyalty rewards for Moderate customers.
- Encourage Offline customers to adopt digital banking through incentives.
- Launch personalized re-engagement campaigns for Dormant Elite customers.

---

## 📁 Repository Structure

```
credit-card-customer-segmentation/
│
├── data/
│   └── Credit Card Customer Data.xlsx
│
├── notebooks/
│   └── credit_card_customer_segmentation.ipynb
│
├── reports/
│   └── credit_card_customer_segmentation_report.pdf
│
├── images/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```
git clone https://github.com/Aryaman-Modi/credit-card-customer-segmentation.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the notebook

```
jupyter notebook
```

4. Run all cells.

---

## 📊 Future Improvements

- Interactive dashboard using Streamlit
- Customer persona visualization
- Automated cluster recommendations
- Deployment as a web application

---

## 👨‍💻 Author

**Aryaman Modi**

Aspiring Data Analyst | Machine Learning Enthusiast

Feel free to connect and explore my other projects!
