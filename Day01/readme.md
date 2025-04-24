# 📅 Day 1: Intro to Python for Data Analysis

Welcome to **Day 1** of the **30 Days of Data Analyst** series!

Today, we’re laying the foundation for data analysis by learning the basics of Python — focusing on variables and data types.

---

## 📚 Topics Covered

- What is Python and why it's used in data analysis
- Declaring and using variables
- Core data types:
  - Integers
  - Floats
  - Strings
  - Booleans
- Type checking using `type()`
- Type conversion (casting)

---

## 🧪 Code Example

```python
Declaring variables
name = 'Chinmay'
age = 25
height = 5.9
is_data_analyst = True

Displaying variables
print(name, age, height, is_data_analyst)

Checking types
print(type(name))        # str
print(type(age))         # int
print(type(height))      # float
print(type(is_data_analyst))  # bool

Type casting
age_str = str(age)
height_int = int(height)
print(age_str, type(age_str))
print(height_int, type(height_int))
