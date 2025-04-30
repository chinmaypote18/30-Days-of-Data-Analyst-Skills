# 📅 Day 5: Python Libraries – NumPy & Pandas

Welcome to **Day 5** of the _30 Days of Data Science_ challenge!  
Today is all about using Python libraries to **manipulate and analyze data**.

---

## 🧠 What You’ll Learn

- ✅ What is NumPy and why it matters
- ✅ Creating arrays and doing stats
- ✅ Creating Pandas DataFrames
- ✅ Filtering, adding columns, and simple operations

---

## 📓 Notebook Preview

In this notebook, you'll:
- Work with NumPy arrays and basic stats 🔢  
- Create and manipulate tables using Pandas 🧾  
- Filter rows and compute totals 📊  
- Practice using real-world-like sales data 💼

---

## 🧪 Sample Exercise

```python
# Create a sales DataFrame
import pandas as pd

sales = pd.DataFrame({
    'Product': ['Book', 'Pen', 'Notebook'],
    'Price': [150, 20, 60],
    'Quantity': [2, 10, 5]
})

# Add total column
sales['Total'] = sales['Price'] * sales['Quantity']
print(sales)
