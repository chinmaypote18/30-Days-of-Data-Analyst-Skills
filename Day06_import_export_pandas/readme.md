# 📅 Day 6: Importing & Exporting Data with Pandas

Welcome to **Day 6** of the _30 Days of Data Science_ challenge!  
Today you’ll learn how to **bring data in and send data out** — a must-have skill for any data analyst.

---

## 🧠 What You’ll Learn

- ✅ Reading `.csv` and `.xlsx` files
- ✅ Exploring data from real files
- ✅ Writing your results to new CSV/Excel files
- ✅ Practicing file-based data workflows

---

## 📓 Notebook Preview

In this notebook, you'll:
- Load external data with `read_csv()`  
- Add new calculated columns  
- Export DataFrames using `to_csv()`  
- Practice file reading and filtering logic 🔁

---

## 🧪 Sample Exercise

```python
# Read CSV and export filtered rows
df = pd.read_csv('sales.csv')
high_sales = df[df['Revenue'] > 1000]
high_sales.to_csv('top_sales.csv', index=False)
