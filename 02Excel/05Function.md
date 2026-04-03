# Session: SUM, AVERAGE, COUNT Functions in Excel/SQL

---

## 1. SUM Functions

| Function | Description | Example |
|----------|-------------|---------|
| `SUM()` | Adds numbers in a range | `=SUM(A1:A10)` → adds values from A1 to A10 |
| `SUMIF()` | Adds numbers if a condition is met | `=SUMIF(A1:A10, ">50")` → adds only values >50 |
| `SUMIFS()` | Adds numbers if multiple conditions are met | `=SUMIFS(B1:B10, A1:A10, ">50", C1:C10, "Yes")` → sum B1:B10 where A>50 and C="Yes" |

**Practical Demo Ideas:**  
- Add all sales amounts.  
- Add sales above a certain target.  
- Add sales for a specific region or category using multiple criteria.  

---

## 2. AVERAGE Functions

| Function | Description | Example |
|----------|-------------|---------|
| `AVERAGE()` | Calculates the average of a range | `=AVERAGE(A1:A10)` |
| `AVERAGEIF()` | Average based on a condition | `=AVERAGEIF(A1:A10, ">50")` |
| `AVERAGEIFS()` | Average based on multiple conditions | `=AVERAGEIFS(B1:B10, A1:A10, ">50", C1:C10, "Yes")` |

**Practical Demo Ideas:**  
- Average marks of students in a class.  
- Average sales above a target.  
- Average attendance for a specific month and department.  

---

## 3. COUNT Functions

| Function | Description | Example |
|----------|-------------|---------|
| `COUNT()` | Counts numeric values in a range | `=COUNT(A1:A10)` |
| `COUNTA()` | Counts non-empty cells (numbers, text, dates) | `=COUNTA(A1:A10)` |
| `COUNTBLANK()` | Counts empty cells | `=COUNTBLANK(A1:A10)` |
| `COUNTIF()` | Counts cells meeting a condition | `=COUNTIF(A1:A10, ">50")` |
| `COUNTIFS()` | Counts cells meeting multiple conditions | `=COUNTIFS(A1:A10, ">50", B1:B10, "Yes")` |

**Practical Demo Ideas:**  
- Count number of students who scored above 50.  
- Count number of products in stock.  
- Count empty fields in a dataset.  

---

## 4. Combined Examples

1. **SUMIF + COUNTIF** – Show total sales and number of sales above a threshold.  
2. **AVERAGEIFS** – Show average marks of students in Class A who scored above 70.  
3. **SUM + COUNT** – Calculate average manually as `SUM(range)/COUNT(range)`.  

---


