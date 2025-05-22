# 📊 Sales & Profit Analysis Report

## 🧠 Overview
This project presents an in-depth analysis of sales and profit data across product categories, regions, and customer behaviors. The goal was to identify **what drives profit**, uncover **underperforming areas**, and assess the **impact of discounts and shipping modes**.

All analysis was performed using **Python** in a **Jupyter Notebook**, with findings summarized below and detailed visualizations in the notebook.

---

## 📁 Project Files

- `PROJECT.ipynb` – Complete exploratory data analysis (EDA)
- `Analysis.docx` – Executive summary and insights report
- `README.md` – Project documentation (this file)

---

## 🛠 Tools & Libraries Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- datetime

---

## 🔍 Key Business Questions & Insights

### 1. 🛒 Which Product Categories Drive the Most Profit?

| Category         | Profit Share | Avg. Profit | Market Share |
|------------------|--------------|-------------|----------------|
| **Technology**     | 50.79%       | 78.75       | 36.40%         |
| Office Supplies  | 42.77%       | 20.33       | 31.30%         |
| Furniture        | 6.44%        | 8.70        | 32.30%         |

- 📈 **Technology** is the most profitable with the highest average profit per order.
- 📦 **Office Supplies** perform well in volume and total profit.
- 🛋 **Furniture** has decent market share but lags in profit.

#### Top Sub-Categories by Profit Share:
- 🖨 **Copiers** – 19.42%
- 📱 **Phones** – 15.54%
- 🎧 **Accessories** – 14.64%

#### Bottom Sub-Categories by Profit Share:
- 🗃 **Supplies**, 🪟 **Bookcases**, and 🪑 **Tables** are loss-making.

---

### 2. 📉 Which Regions/States Are Underperforming?

| Region  | Market Share | Profit Share |
|---------|--------------|--------------|
| West    | 31.58%       | 37.86%       |
| East    | 29.55%       | 31.96%       |
| Central | 21.82%       | 13.86%       |
| South   | 17.05%       | 16.32%       |

- ✅ **West** leads in both market and profit share.
- ⚠️ **Central** has a large market but low profit — underperformance.
- 🛑 **Texas** and **Ohio** are the biggest loss-making states.

---

### 3. ⏱ What is the Average Delivery Time?

- 📦 Average delivery time: **~4 days**
- 🏙 **District of Columbia** has the slowest average: **5 days 16 hours**
- Delivery time is fairly consistent across **regions and categories**.
- 🎨 **Art** takes slightly longer to deliver.

---

### 4. 💸 Is There a Relationship Between Discount and Profit?

- Correlation between **discount and profit**: **-0.219**
- 🔻 Higher discounts tend to **reduce profitability**
- Discounts have **little effect on boosting sales**

---

### 5. 🚚 How Do Shipping Modes Affect Profit?

| Shipping Mode   | Profit Share | Avg. Delivery Time |
|------------------|--------------|---------------------|
| Standard Class   | 57.29%       | 5 days              |
| Second Class     | 20.06%       | 3 days 5 hours      |
| First Class      | 17.10%       | 2 days 4 hours      |
| Same Day         | 5.55%        | 0 days 1 hour       |

- 🥇 **First Class** has the **highest average profit**
- 🔄 **Standard Class** dominates in volume and total profit
- ⚡ **Same Day** is fastest, but accounts for smallest share

---

## ✅ Summary

- **Technology** and **Copiers/Phones** drive the most profit.
- **Tables**, **Bookcases**, and **Supplies** are not profitable.
- The **Central** region and **Texas/Ohio** need strategic review.
- **Discounting** should be done cautiously — it reduces profit.
- **First Class** shipping is most profitable on a per-order basis.

---

## 👤 Author

**Japmanpreet Singh**  
📧 [japmanpreetsingh2007@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/japmanpreet-singh-467173320/)  
🐙 [GitHub Profile](https://github.com/Japmanpreet-ctrl)

---

## ⭐ If you found this useful
Give this project a ⭐ on GitHub or share it on LinkedIn!

---

## 📜 License

This project is open-source and licensed under the [MIT License](LICENSE).

