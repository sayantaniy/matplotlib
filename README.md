# Matplotlib 

## What is Matplotlib?

Matplotlib is a Python library used for **data visualization**. It helps create **plots, charts, and graphs** to understand data visually.

Most commonly used module: **pyplot**

---

## Why Matplotlib?

* Visualize data clearly
* Helps in **EDA (Exploratory Data Analysis)**
* Essential for **Data Science & ML**
* Highly customizable plots

---

## Installation & Import

```bash
pip install matplotlib
```

```python
import matplotlib.pyplot as plt
```

---

## Basic Plot

```python
x = [1, 2, 3]
y = [4, 5, 6]

plt.plot(x, y)
plt.show()
```

---

## Labels & Title

```python
plt.plot(x, y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Simple Line Plot')
plt.show()
```

---

## Common Plot Types

### 1. Line Plot

```python
plt.plot(x, y)
```

### 2. Scatter Plot

```python
plt.scatter(x, y)
```

### 3. Bar Chart

```python
plt.bar(x, y)
```

### 4. Histogram

```python
plt.hist(y)
```

### 5. Pie Chart

```python
plt.pie(y)
```

---

## Figure & Size

```python
plt.figure(figsize=(6,4))
```

---

## Grid & Legend

```python
plt.grid()
plt.legend()
```

---

## Multiple Lines

```python
plt.plot(x, y, label='Line 1')
plt.plot(x, [i*2 for i in y], label='Line 2')
plt.legend()
```

---

## Styling (Basic)

```python
plt.plot(x, y, linestyle='--', marker='o')
```

---

## Saving a Plot

```python
plt.savefig('plot.png')
```

---

## Using NumPy with Matplotlib

```python
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.show()
```

---

## Matplotlib vs Seaborn

| Feature  | Matplotlib | Seaborn    |
| -------- | ---------- | ---------- |
| Control  | High       | Medium     |
| Ease     | Medium     | Easy       |
| Based on | Low-level  | High-level |

---

## Where Matplotlib is Used

* Data Visualization
* Machine Learning Results
* Research & Reports

---

## One-Line Summary

**Matplotlib = Visualize Data Clearly Using Python** 📊
