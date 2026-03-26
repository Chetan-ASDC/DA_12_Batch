#  Number System Conversion Guide

##  Introduction
A number system defines how numbers are represented using a base (radix).  
Common number systems:
- Decimal (Base 10)
- Binary (Base 2)
- Octal (Base 8)
- Hexadecimal (Base 16)

---

##  1. Decimal to Binary

### Method:
Divide the number by 2 repeatedly and record remainders.

### Example: Convert 10 to Binary

| Step | Division | Quotient | Remainder |
|------|----------|----------|----------|
| 1    | 10 ÷ 2   | 5        | 0        |
| 2    | 5 ÷ 2    | 2        | 1        |
| 3    | 2 ÷ 2    | 1        | 0        |
| 4    | 1 ÷ 2    | 0        | 1        |

 Binary = **1010**

---

##  2. Binary to Decimal

### Method:
Multiply each digit with powers of 2.

### Example: Convert 1011 to Decimal

\[
(1 × 2^3) + (0 × 2^2) + (1 × 2^1) + (1 × 2^0)
\]

 Decimal = **11**

---

##  3. Decimal to Octal

### Method:
Divide by 8 repeatedly.

### Example: Convert 65 to Octal

| Step | Division | Quotient | Remainder |
|------|----------|----------|----------|
| 1    | 65 ÷ 8   | 8        | 1        |
| 2    | 8 ÷ 8    | 1        | 0        |
| 3    | 1 ÷ 8    | 0        | 1        |

 Octal = **101**

---

##  4. Decimal to Hexadecimal

### Method:
Divide by 16 repeatedly.

### Example: Convert 254 to Hexadecimal

| Step | Division | Quotient | Remainder |
|------|----------|----------|----------|
| 1    | 254 ÷ 16 | 15       | 14 (E)   |
| 2    | 15 ÷ 16  | 0        | 15 (F)   |

 Hexadecimal = **FE**

---

##  5. Binary to Octal (Shortcut)

### Rule:
Group binary digits in sets of 3 (from right).

### Example: 110101

- Groups: 110 101  
- Values: 6   5  

 Octal = **65**

---

##  6. Binary to Hexadecimal (Shortcut)

### Rule:
Group binary digits in sets of 4 (from right).

### Example: 10101111

- Groups: 1010 1111  
- Values: A     F  

 Hexadecimal = **AF**

---

##  Important Tips

- Binary → Octal = Group in 3 digits
- Binary → Hex = Group in 4 digits
- Always read remainders **bottom to top**
- Practice is key to mastering conversions

---

##  Practice Questions

1. Convert 25 (Decimal) to Binary  
2. Convert 1110 (Binary) to Decimal  
3. Convert 100 (Decimal) to Octal  
4. Convert 2F (Hex) to Decimal  
5. Convert 110011 (Binary) to Hex  

---

##  Conclusion
Understanding number system conversions is essential for:
- Computer Science
- Programming
- Data Analysis
- Digital Electronics

---