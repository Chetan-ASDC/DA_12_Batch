# Mathematical Evaluation of Descriptive Statistics  


This section explains **what each term means**, **why it is used**, and **how to calculate it**, step by step.  


---

## 1. Mean (Arithmetic Mean)

### What is Mean?
The **mean** is the **average value** of a dataset.  
It represents the **overall level** of the data.

 Used when we want a **single value** to represent all observations.

---

### Formula
```

x̄ = (Σx) / n

Where:
Σx = Sum of all observations (all data values added together)
n = Total number of observations (number of values in the dataset)

```

---

### Example
Marks of 5 students:

```

10, 20, 30, 40, 50

```


**Step 1:** Add all values  
10 + 20 + 30 + 40 + 50 = 150  

**Step 2:** Divide by number of values  
\[
x̄ = 150 / 5 = 30
\]

 **Mean = 30**

---

## 2. Median

### What is Median?
The **median** is the **middle value** of a dataset when arranged in order.

 Useful when data contains **very high or very low values** (outliers).

---

### Steps to Find Median
1. Arrange data in ascending order  
2. Check total number of values  

---

### Example 1: Odd Number of Values
Data:
```

5, 10, 15, 20, 25

```


Middle value = **15**

 **Median = 15**

---

### Example 2: Even Number of Values
Data:
```

5, 10, 15, 20

```


Two middle values = 10 and 15  

\[
Median = (10 + 15) / 2 = 12.5
\]

**Median = 12.5**

---

## 3. Mode

### What is Mode?
The **mode** is the value that **appears most frequently** in the dataset.

 Useful for **categorical data** (sizes, products, choices).

---

### Example
Data:
```
2, 4, 6, 6, 8, 10

```

Value **6** occurs most often.

 **Mode = 6**

---

## 4. Range

### What is Range?
The **range** shows the **total spread of the data**.

 It tells us how far the data values are from each other.

---

### Formula
\[
Range = Maximum value − Minimum value
\]

---

### Example
Data:
```
12, 18, 25, 30, 40

```


Maximum = 40  
Minimum = 12  

\[
Range = 40 - 12 = 28
\]

 **Range = 28**

---

## 5. Variance

### What is Variance?
Variance measures **how much data values differ from the mean** (on average).

 It uses **squared deviations**, so values are always positive.

---

### Formula (Population Variance)
\[
σ² = Σ(x − x̄)² / N
\]

---

### Example
Data:
```
2, 4, 6

```

#### Step 1: Find Mean
\[
x̄ = (2 + 4 + 6) / 3 = 4
\]

#### Step 2: Calculate deviations

| x | x − x̄ | (x − x̄)² |
|--|------|----------|
| 2 | -2 | 4 |
| 4 | 0 | 0 |
| 6 | 2 | 4 |

#### Step 3: Apply formula
\[
σ² = (4 + 0 + 4) / 3 = 8 / 3 = 2.67
\]

 **Variance = 2.67**

---

## 6. Standard Deviation

### What is Standard Deviation?
The **standard deviation** is the **square root of variance**.

 It shows how **closely data values are grouped around the mean**.

---

### Formula
\[
σ = √σ²
\]

---

### Example
\[
σ = √2.67 ≈ 1.63
\]

### Interpretation
- **Low SD** → Data values are close to mean  
- **High SD** → Data values are widely spread  

---

## 7. Summary of All Measures

| Measure | What it Shows |
|------|--------------|
| Mean | Average value |
| Median | Middle value |
| Mode | Most frequent value |
| Range | Total spread |
| Variance | Average squared deviation |
| Standard Deviation | Actual data spread |

---

## 8. One Complete Example

Data:
```
5, 7, 9, 10, 10, 12

```


- Mean = 8.83  
- Median = 9.5  
- Mode = 10  
- Range = 7  

---

## 9. Conclusion

- **Mean** represents overall average  
- **Median** is best for uneven data  
- **Mode** identifies most common value  
- **Range** shows data spread  
- **Standard Deviation** shows consistency  

 These measures form the **foundation of data analysis**.

---

###  Practice Question
Calculate **Mean, Median, Mode, Range, Variance, and Standard Deviation** for:

```
8, 10, 12, 14, 16
```