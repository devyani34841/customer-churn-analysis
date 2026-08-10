# Customer Churn Analysis and Customer Intelligence

## 📌 About the Project

This project focuses on analyzing customer churn and understanding customer behavior using data analysis techniques.

This is a **learning and practice project based on a YouTube tutorial**. I used this project to understand and practice Python, SQL, data cleaning, feature engineering, exploratory data analysis, and data visualization.

The project works with customer, subscription, and support-related data to identify churn patterns and understand factors associated with customer churn.

---

## 🎯 Project Objective

The main objectives of this project are:

* Analyze customer churn and retention
* Calculate the overall churn rate
* Calculate the retention rate
* Identify churn patterns across different customer segments
* Analyze customer subscription information
* Analyze monthly churn trends
* Study the relationship between customer attributes and churn
* Analyze customer support escalations
* Create churn-risk categories
* Perform correlation analysis
* Use SQL for database operations and analysis
* Create meaningful data visualizations

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SQLite**
* **SQL**
* **Jupyter Notebook**
* **Microsoft Excel**

---

## 📂 Dataset

The project uses customer-related data stored in an Excel file and SQLite database.

The Excel dataset contains multiple sheets related to:

* Customer information
* Subscription information
* Customer support information

The SQLite database is used to store and work with these datasets using SQL.

---

## 🔄 Project Workflow

The project follows these main steps:

### 1. Data Import

* Import customer data from Excel
* Create and connect to a SQLite database
* Convert Excel sheets into SQLite tables
* Load database tables into Pandas DataFrames

### 2. Data Cleaning

The project performs different data-cleaning operations, including:

* Renaming columns
* Removing unnecessary columns
* Changing data types
* Standardizing data values
* Handling missing values

### 3. Feature Engineering

A new `churn_flag` column is created.

A customer is considered churned when their cancellation date is available.

```python
churn_flag = 1 → Customer churned
churn_flag = 0 → Customer did not churn
```

### 4. Data Analysis

The project analyzes:

* Churn rate
* Retention rate
* Customer tenure
* Monthly charges
* Revenue-related metrics
* Customer support escalations
* Churn risk
* Customer segments

### 5. Data Visualization

The project uses Matplotlib and Seaborn to create visualizations such as:

* Monthly churn trends
* Churn analysis by customer segments
* Correlation heatmaps
* Customer-related comparisons

### 6. Pivot Table Analysis

Pivot tables are used to analyze:

* Churn by plan type
* Monthly charges
* Number of customers
* Churn rates

### 7. SQL Analysis

The project also includes SQL practice using SQLite and Python.

It demonstrates:

* Creating SQL tables
* Inserting data
* Reading data using SQL queries
* Connecting SQLite with Pandas

---

## 📊 Key Analysis

Some of the important analysis performed in this project includes:

### Churn Rate

The percentage of customers who have churned.

### Retention Rate

The percentage of customers who have remained with the service.

### Monthly Churn Trend

Analyzes how the number of churned customers changes over time.

### Churn Risk

Customers are categorized based on churn-related information to help understand potential high-risk customers.

### Customer Support Analysis

Customer escalations and support-related information are analyzed to understand their relationship with churn.

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── README.md
│
├── churn_analysis.ipynb
│
├── customer_churn_data_raw.xlsx
│
└── customer_churn.db
```

---

## ▶️ How to Run the Project

### Step 1: Clone the repository

```bash
git clone <your-github-repository-link>
```

### Step 2: Open the project folder

```bash
cd customer-churn-analysis
```

### Step 3: Install the required Python libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

### Step 4: Open the notebook

Open:

```text
churn_analysis.ipynb
```

using Jupyter Notebook or VS Code.

### Step 5: Run the notebook

Run the cells from top to bottom.

Make sure the Excel file and SQLite database are present in the same project folder.

---

## 📌 Project Files

| File                           | Description                             |
| ------------------------------ | --------------------------------------- |
| `churn_analysis.ipynb`         | Main Python analysis notebook           |
| `customer_churn_data_raw.xlsx` | Raw customer dataset                    |
| `customer_churn.db`            | SQLite database containing project data |
| `README.md`                    | Project documentation                   |

---

## 📚 What I Learned

Through this project, I practiced:

* Data cleaning using Pandas
* Data preprocessing
* Feature engineering
* Working with multiple DataFrames
* Joining and merging datasets
* Exploratory Data Analysis (EDA)
* Churn and retention analysis
* SQL with SQLite
* Data visualization
* Matplotlib
* Seaborn
* Pivot tables
* Basic business analysis

---

## 🎓 Learning Source

This project was completed as a **learning/practice project based on a YouTube tutorial**.

**Original Tutorial:**
https://www.youtube.com/watch?v=tTtI2arH214&t=2349s

**Original Creator:** Rishabh Mishra

The tutorial was used as a learning reference to understand the project workflow and data-analysis concepts.

---
