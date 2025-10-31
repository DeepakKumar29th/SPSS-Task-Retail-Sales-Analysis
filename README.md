# 📊 Retail Sales Data Preparation & Discount Pattern Analysis

### 🛒 Data Analytics | Retail Domain | Data Cleaning & Business Insight SPSS Task

---

## 📎 Project Overview

This project focuses on cleaning, transforming, and analyzing retail sales transaction data to identify spending patterns and understand the logic behind discount allocation.  
The objective is to convert raw sales data into high-quality, analysis-ready data and generate meaningful retail business insights.

---

## 🎯 Objectives

- Preprocess and clean the retail dataset  
- Fix data type issues, missing values, and duplicates  
- Detect and handle outliers  
- Create calculated/derived fields (discount logic)  
- Perform exploratory data analysis  
- Understand customer purchase behavior and discount distribution  

---

## 📝 Problem Statement

The retail store provided raw transactional sales data which was **not prepared for analysis**.  
The dataset contained multiple data quality issues such as:

- ❌ Missing or blank values  
- ❌ Inconsistent data formatting  
- ❌ Duplicate entries  
- ❌ Unstructured category and item labels  
- ❌ Outliers in spending and quantity values  
- ❌ No clear discount logic column present  

These problems would negatively affect analysis, so the data needed to be cleaned, standardized, and validated before deriving insights.

### 🎯 Business Requirement

The task was to:

- Clean and prepare the retail transactional dataset
- Identify the logic behind discount applicability
- Create a calculated column for discount based on spending criteria
- Analyze customer behavior and spending patterns after cleaning

### ✅ Discount Rule Applied

A discount was applied based on total purchase value:

| Condition | Discount |
|----------|---------|
| Total Spent > ₹70 | **30% discount applied** |
| Total Spent ≤ ₹70 | **No discount provided** |

---

## 🧰 Tools Used

| Tool | Purpose |
|------|--------|
| **IBM SPSS Modeler 18.6** | Data cleaning, transformation, and analysis |
| **Excel / CSV File** | Initial dataset storage and structure |

---

## 📂 Dataset Description

**File:** `retail_store_sales.csv`

| Feature | Description |
|--------|-------------|
| Transaction ID | Unique identifier for each transaction |
| Customer ID | Unique identifier for each customer |
| Category | Product category purchased |
| Item | Product/item name |
| Price Per Unit | Cost per individual unit |
| Quantity | Number of units purchased |
| Total Spent | Total bill amount (Price × Quantity) |
| Payment Method | Mode of payment used by customer |
| Location | Store location where purchase occurred |
| Transaction Date | Date of purchase |

---

## 🧠 Tasks Performed

### ✅ Data Preparation Steps

| Step | Task | Purpose |
|------|------|--------|
| 1️⃣ | Import Dataset | Load data |
| 2️⃣ | Assign Data Types | Fix numeric/text fields |
| 3️⃣ | Handle Missing Values | Improve completeness |
| 4️⃣ | Remove Duplicates | Ensure data accuracy |
| 5️⃣ | Standardize Categories | Uniform labels |
| 6️⃣ | Create Derived Field | Discount rule identification |
| 7️⃣ | Outlier Detection & Treatment | Validate numerical values |

---

## 🔍 Key Insights

- Discount is mostly given to **high-spending customers**
- Quantity does **not directly affect** discount eligibility
- Customers spending above ₹70 triggered a **30% discount**
- Discount strategy is value-based, not product-volume-based
- Clean data improved clarity of purchasing patterns and discount efficiency

---

## 📦 Outputs

- ✅ Cleaned & structured dataset  
- ✅ Derived discount logic column  
- ✅ Summary statistics & charts  
- ✅ Final processed file  
- ✅ Documentation & analysis notes  

---

## 🖼️ Project Workflow Screenshot

<img width="1920" height="1080" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/28a6faab-d576-483f-af9f-c516d25735c9" />

---

## 👥 Project Contributors  

| Members |
|--------|
| **Devansh Kumar Singh** |
| **Deepak Kumar** |
| **Daya Yadav** |

---

### ✅ Thank you for visiting our project!
