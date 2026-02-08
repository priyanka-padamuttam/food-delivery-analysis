# 🍔 Food Delivery Performance & Customer Satisfaction Analysis


## 📌 Project Overview

This project analyzes food delivery order data to understand **delivery efficiency**, **customer satisfaction**, and **day-wise behavioral patterns** using **Python and data visualization**.

The goal is to identify:

- Operational bottlenecks  
- Factors affecting customer ratings  
- Patterns across cities and days of the week  

This project is suitable for **data analyst portfolios** and **exploratory data analysis (EDA)** demonstrations.

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – data manipulation
- **Matplotlib** – data visualization
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📑 Dataset Description

The dataset contains simulated food delivery order data with the following fields:

| Column Name | Description |
|------------|-------------|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| City | City where the order was delivered |
| Delivery_Partner | Delivery service provider |
| Distance_km | Delivery distance in kilometers |
| Delivery_Time | Delivery time in minutes |
| Order_Value | Order amount |
| Rating | Customer rating (1–5) |

---

## 🔄 Step 1: Data Loading & Preparation

- Loaded CSV data using **Pandas**
- Converted `Order_Date` into datetime format
- Extracted:
  - **Day of Week**
  - **Day Number (0–6)** for proper sorting

### Why this step matters
Accurate date handling is critical for **time-based analysis** and **day-wise insights**.

---

## 🚚 Step 2: Delivery Performance Analysis

### 📊 Visualization 1: Average Delivery Time by City
**Chart Type:** Bar Chart  

**Purpose:**
- Compare delivery efficiency across cities  
- Identify cities with higher delivery delays  

**Insight:**  
Some cities show consistently higher average delivery times, indicating possible traffic or distance challenges.

---

### 📈 Visualization 2: Distance vs Delivery Time
**Chart Type:** Scatter Plot  

**Purpose:**
- Analyze relationship between distance and delivery time  

**Insight:**  
Delivery time generally increases with distance, confirming a positive correlation between the two variables.

---

## ⭐ Step 3: Customer Satisfaction Analysis

### 📉 Visualization 3: Delivery Time vs Rating
**Chart Type:** Scatter Plot  

**Purpose:**
- Understand how delivery speed impacts customer ratings  

**Insight:**  
Longer delivery times tend to receive lower ratings, highlighting delivery speed as a key satisfaction driver.

---

### 📊 Visualization 4: Average Rating by City
**Chart Type:** Bar Chart  

**Purpose:**
- Compare customer satisfaction across cities  

**Insight:**  
Some cities consistently receive higher ratings, possibly due to better delivery infrastructure or service quality.

---

### 📊 Visualization 5: Rating by Delivery Partner
**Chart Type:** Bar Chart  

**Purpose:**
- Evaluate performance of delivery partners  

**Insight:**  
Delivery partners show differences in average ratings, which may indicate service-level variations.

---

## 📅 Step 4: Day-wise Behavioral Insights (Key Analysis)

### 📊 Visualization 6: Average Rating by Day of Week
**Chart Type:** Bar Chart  

**Purpose:**
- Analyze how customer satisfaction varies by day  

**Key Insight:**
- **Lowest ratings:** Thursday  
- **Highest ratings:** Friday, Saturday, Sunday  

This suggests better service perception or relaxed delivery expectations during weekends.

---

### 📊 Visualization 7: Weekend vs Weekday Ratings
**Chart Type:** Bar Chart  

**Purpose:**
- Simplify day-wise analysis into business-friendly categories  

**Insight:**  
Weekend orders receive higher average ratings compared to weekdays.

---

## 🧠 Key Business Insights

- Delivery speed strongly influences customer ratings  
- Customer satisfaction peaks on weekends  
- Thursdays show the lowest average ratings  
- Distance and city-specific factors impact delivery efficiency  

---

## 📌 Conclusion

This analysis demonstrates how **exploratory data analysis and visualization** can uncover actionable insights in food delivery operations.

The findings can help businesses:
- Improve delivery efficiency  
- Optimize staffing on low-performing days  
- Focus on customer satisfaction drivers  

---

## 🚀 Future Enhancements

- Add **Power BI** or **Tableau** dashboard  
- Include **time-of-day analysis**  
- Apply **predictive modeling** for delivery time or ratings  

---

## 👤 Author

👤 Author  
Priyanka Padamuttam  
Aspiring Data Analyst | Python | SQL | Data Analysis


## ✅ How to Run

1. Clone the repository  
2. Open `Food_Delivery_Analysis.ipynb`  
3. Run cells top to bottom  
