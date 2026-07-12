# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI. The objective is to identify customer purchasing patterns, product preferences, revenue trends, and subscription behavior to support business decision-making.

The project follows a complete data analytics workflow, starting from data cleaning and exploration in Python, storing the processed data in PostgreSQL, performing SQL-based business analysis, and finally creating an interactive Power BI dashboard.

---

## 📂 Dataset

- **Dataset:** Customer Shopping Trends
- **Records:** 3,900
- **Features:** 18
- **Source:** Kaggle

### Key Attributes

- Customer ID
- Age
- Gender
- Category
- Item Purchased
- Purchase Amount
- Subscription Status
- Shipping Type
- Discount Applied
- Review Rating
- Previous Purchases
- Frequency of Purchases
- Season
- Size
- Color

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|----------|
| Python | Data Cleaning & EDA |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| PostgreSQL | Database |
| SQL | Business Analysis |
| Power BI | Dashboard & Visualization |
| Jupyter Notebook | Development Environment |
| Git & GitHub | Version Control |

---

## 📊 Project Workflow

### 1. Data Loading

- Loaded CSV dataset into Pandas
- Verified dataset structure
- Explored rows and columns

---

### 2. Exploratory Data Analysis (EDA)

Performed:

- Data inspection
- Summary statistics
- Missing value analysis
- Duplicate check
- Data type verification
- Category distribution
- Numerical feature analysis

---

### 3. Data Cleaning

Performed the following preprocessing:

- Removed duplicate records
- Renamed columns to snake_case
- Handled missing values
- Imputed missing Review Rating values using median by product category
- Dropped redundant columns
- Created Age Group feature
- Created Purchase Frequency Days feature

---

### 4. Database Integration

Connected Python to PostgreSQL using SQLAlchemy.

Loaded cleaned data into PostgreSQL for SQL analysis.

---

### 5. SQL Business Analysis

Performed business analysis including:

- Revenue by Gender
- Revenue by Age Group
- Revenue by Category
- Top Rated Products
- Subscriber vs Non-Subscriber Analysis
- Shipping Type Analysis
- Customer Segmentation
- Top Products by Category
- Repeat Customer Analysis
- Discount Analysis

---

### 6. Power BI Dashboard

Developed an interactive dashboard with:

#### KPI Cards

- Total Customers
- Average Purchase Amount
- Average Review Rating

#### Charts

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution

#### Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type
- Reset Filters Button

---

## 📈 Dashboard Preview

> Add your dashboard screenshot here.

Example:

```
images/dashboard.png
```

---

## 📌 Key Insights

- Clothing generated the highest revenue.
- Young Adult customers contributed the highest sales.
- Subscribers represented approximately 27% of customers.
- Non-subscribers accounted for nearly 73%.
- Average customer purchase amount was approximately $59.76.
- Average review rating was 3.75.

---

## 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   ├── Customer_Behavior.pbix
│   └── dashboard.png
│
├── report/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── README.md
│
└── requirements.txt
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Run all notebook cells.

### PostgreSQL

- Create a PostgreSQL database.
- Update the connection credentials.
- Load the cleaned DataFrame into PostgreSQL.

### Power BI

Open the `.pbix` file to explore the interactive dashboard.

---

## 📷 Dashboard

*<img width="1416" height="782" alt="Screenshot 2026-07-12 230511" src="https://github.com/user-attachments/assets/4a0c53db-3033-46d8-a13a-9852fb30f339" />
*

---

## 📄 Project Report

A detailed report explaining the complete workflow, SQL analysis, business insights, and recommendations is included in this repository.

---

## 🚀 Future Improvements

- Predict customer purchase behavior using Machine Learning
- Build customer segmentation using clustering
- Deploy dashboard online
- Automate ETL pipeline
- Add real-time analytics

---

## 👩‍💻 Author

**Ashna K**

- LinkedIn: https://www.linkedin.com/in/ashnakottakkal/
- GitHub: https://github.com/ashnak7994

---# customer-behavior-analysis
