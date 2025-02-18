# 🚴‍♂️ Bike Sales Analysis using Excel 📊  

This project analyzes a retail dataset containing **bike sales data**, aiming to answer key business questions related to **markets, sales distribution, and profitability**. The analysis was conducted using **Microsoft Excel**, leveraging functions, pivot tables, and slicers for data visualization and insights.  

---

## 📝 Business Questions Answered

1️⃣ **In which markets does Germany have customers?**  
2️⃣ **Which country has sales in all markets age group?**  
3️⃣ **What are the most profitable markets by country, age group, and gender?**  

---

## 🛠️ Tools & Techniques Used  

- **Microsoft Excel** 💻    
- **Pivot Tables & Charts** 📊📈 

---

## 🔍 Data Analysis Steps  

### 1️⃣ Germany’s Market Presence 🌍  
Using **Pivot Tables**, I filtered the dataset to identify the **Age categories where Germany has customers**.  

✅ **Key Insight**: Germany has customers in the following Age groups:  
🔹 **(Germany's market presence is limited to the Adult age group (35-64))**  

📸 **Visualization**:  
![Germany Market Customers](link_to_your_image_here)  

---

### 2️⃣ Countries with Sales Across All Age Groups 🌎  
By using **Pivot Tables**, I determined which countries made sales across **all age group**.  

✅ **Key Finding**:  
- The countries with sales in **every age group** are **(Australia and the United kingdom)**.  

📸 **Visualization**:  
![Final Pivot table](https://github.com/user-attachments/assets/269f423b-64b4-499e-b349-8a01d3241cb3)


---

### 3️⃣ Most Profitable Markets by Country, Age Group, and Gender 💰  
Using **Pivot Charts**, I visualized profitability trends across **countries, age groups, and genders**.  

✅ **Findings**:  
- **Most profitable country**: 🏆 **(United States)**  
- **Most profitable age group**: 📊 **(Adults 35-64)**  
- **Most profitable gender**: 🚻 **(Male)**  

📸 **Visualization**:  

![Profitability](https://github.com/user-attachments/assets/091357b7-77ef-442c-800e-fc75a005ce7f)
  

---

## 📅 How to Explore the Analysis  

1️⃣ **Download the dataset** from this repository.  
2️⃣ **Open it in Microsoft Excel**.  
3️⃣ Navigate to **Pivot Tables and Charts** to explore insights interactively.  
4️⃣ Use **Slicers** to filter data dynamically.  

## ⚠️ Challenges Faced & Solutions  

### Duplicate Country Entries in Pivot Table  
**Issue:** When creating the Pivot Table, "United States" appeared **three times** instead of once.  

**Cause:** This happened due to **inconsistent spacing** in the dataset, where extra spaces were present in some entries of the "Country" column.  

**Solution:** I resolved this by applying the `TRIM()` function to the **Country Name** column, which removed any leading or trailing spaces. After refreshing the Pivot Table, "United States" appeared correctly as a single entry. It was a valuable learning experience for me because it highlighted the importance of data preparation in ensuring smooth analysis. 

