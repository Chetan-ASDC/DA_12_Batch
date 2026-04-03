#  Excel Practice Tasks – Logical Formulas

**Topics Covered:**  
IF · AND · OR · NOT · IFERROR · Nested IF  

---

##  Task 1: Pass / Fail using IF

### Dataset

| Roll No | Student Name | Marks | Result |
|--------|--------------|-------|--------|
| 1 | Aman | 78 | |
| 2 | Bharti | 35 | |
| 3 | Rohan | 62 | |
| 4 | Deepa | 40 | |
| 5 | Farhan | 28 | |

### Task
- If Marks ≥ 40 → Pass  
- Else → Fail  

---

##  Task 2: Salary Bonus Check (IF)

### Dataset

| Employee Name | Salary | Bonus Status |
|--------------|--------|--------------|
| Rohit | 28000 | |
| Simran | 45000 | |
| Vijay | 52000 | |
| Nisha | 30000 | |

### Task
- Salary ≥ 40000 → Bonus  
- Else → No Bonus  

---

##  Task 3: Grade Calculation (Nested IF)

### Dataset

| Student Name | Marks | Grade |
|--------------|-------|-------|
| Aman | 82 | |
| Bharti | 67 | |
| Rohan | 45 | |
| Deepa | 33 | |
| Farhan | 90 | |

### Task
- ≥ 75 → A  
- ≥ 60 → B  
- ≥ 40 → C  
- < 40 → Fail  

---

##  Task 4: Job Eligibility (AND)

### Dataset

| Name | Age | Experience (Years) | Eligible |
|------|-----|-------------------|----------|
| Rohit | 25 | 2 | |
| Simran | 20 | 1 | |
| Vijay | 30 | 5 | |
| Nisha | 22 | 0 | |

### Task
- Age ≥ 21 AND Experience ≥ 1 → Eligible  

---

##  Task 5: Exam Eligibility (AND)

### Dataset

| Student Name | Attendance % | Assignment Submitted | Eligible |
|--------------|--------------|---------------------|----------|
| Aman | 85 | Yes | |
| Bharti | 72 | Yes | |
| Rohan | 90 | No | |
| Deepa | 80 | Yes | |

### Task
- Attendance ≥ 75 AND Assignment = Yes  

---

##  Task 6: Discount Logic (OR)

### Dataset

| Customer Name | Purchase Amount | Membership | Discount |
|--------------|-----------------|------------|----------|
| Aakash | 9000 | No | |
| Bhavna | 12000 | No | |
| Rohan | 4000 | Yes | |
| Divya | 3000 | No | |

### Task
- Purchase ≥ 10000 OR Membership = Yes  

---

##  Task 7: Loan Approval (OR)

### Dataset

| Applicant | Salary | CIBIL Score | Loan Status |
|----------|--------|-------------|-------------|
| Rohit | 35000 | 720 | |
| Simran | 25000 | 680 | |
| Vijay | 50000 | 650 | |
| Nisha | 20000 | 600 | |

### Task
- Salary ≥ 40000 OR CIBIL ≥ 700  

---

##  Task 8: Attendance Status (NOT)

### Dataset

| Name | Present | Status |
|------|---------|--------|
| Aman | TRUE | |
| Bharti | FALSE | |
| Rohan | TRUE | |
| Deepa | FALSE | |

### Task
- If NOT Present → Absent  
- Else → Present  

---

##  Task 9: Safe Division (IFERROR)

### Dataset

| Number 1 | Number 2 | Result |
|---------|----------|--------|
| 10 | 2 | |
| 15 | 0 | |
| 20 | 5 | |
| 8 | 0 | |

### Task
- Divide Number 1 by Number 2  
- If error → show "Invalid"  

---

##  Task 10: Performance Evaluation (Combined Logic)

### Dataset

| Employee Name | Targets Achieved | Attendance % | Performance |
|--------------|-----------------|--------------|-------------|
| Raj | 45 | 92 | |
| Sunita | 38 | 85 | |
| Manoj | 50 | 95 | |
| Kavita | 30 | 70 | |

### Task
- Attendance ≥ 90 AND Targets ≥ 40 → Excellent  
- Attendance ≥ 80 → Good  
- Else → Needs Improvement  

---

