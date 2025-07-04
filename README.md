# 📊  Simple Sales Dashboard 

## 🎯 Objective
To build an interactive sales dashboard using Power BI that highlights sales trends across product categories, regions, and time. The dashboard enables key business insights for decision-making.

---

## 📁 Dataset
**File Name:** `Superstore_Sales.csv`  
**Columns Included:**
- `Order Date`
- `Region`
- `Category`
- `Sales`
- `Profit`

---

## 🛠️ Tools Used
- **Power BI Desktop** for data visualization
- **DAX** for calculated columns (e.g., Month-Year)


---

## 📌 Key Steps

1. **Data Loading & Cleaning**
   - Loaded CSV into Power BI
   - Converted `Order Date` to Date type
   - Created a `Month-Year` column using DAX:
     ```DAX
     Month-Year = FORMAT([Order Date], "MMM-yyyy")
     ```

2. **Visualizations Created**
   - 📈 **Line Chart**: Monthly Sales Trend
   - 📊 **Bar Chart**: Sales by Region
   - 🍩 **Donut Chart**: Sales by Product Category

3. **Slicers/Filters**
   - Region and Category used as interactive filters

---

## 💡 Key Insights

1. The **West region** had the highest sales in **Q3**.
2. **Technology** category generated the most revenue.
3. Sales **peaked in December** due to year-end purchases.

--



