# Lookup Functions Practice (VLOOKUP, HLOOKUP, XLOOKUP)

---

##  Sheet: Employee_Data

| EmployeeID | Name          | Department | Location   | Salary | JoiningYear |
|-----------:|---------------|------------|------------|-------:|------------:|
| E101 | Rahul Sharma | Sales     | Mumbai     | 45000 | 2019 |
| E102 | Ananya Gupta | HR        | Delhi      | 52000 | 2018 |
| E103 | Rohit Verma  | IT        | Bangalore  | 65000 | 2020 |
| E104 | Neha Singh   | Finance   | Pune       | 58000 | 2017 |
| E105 | Aman Kumar  | Marketing | Mumbai     | 48000 | 2021 |
| E106 | Pooja Mehta | IT        | Chennai    | 62000 | 2019 |
| E107 | Suresh Rao  | Sales     | Hyderabad  | 47000 | 2020 |
| E108 | Kavita Iyer | HR        | Bangalore  | 54000 | 2016 |

---

##  Sheet: Department_Bonus (Horizontal Table)

| Department | Sales | HR | IT | Finance | Marketing |
|------------|------:|---:|---:|--------:|----------:|
| Bonus %    | 10%   | 8% | 12%| 15%     | 9% |

---

##  Sheet: Search_Input

| EmployeeID | Name |
|------------|------|
| E104 | Rohit Verma |

---

#  Practice Tasks (15)

##  VLOOKUP Tasks (1–6)

1. Find the **Name** of employee using `EmployeeID` from `Search_Input`.
2. Find the **Department** of employee with ID **E103**.
3. Find the **Salary** of employee **Neha Singh** using VLOOKUP.
4. Get the **Location** of employee **E107**.
5. If `EmployeeID` is not found, display **"Not Found"**.
6. Find the **JoiningYear** of employee **E101**.

---

##  HLOOKUP Tasks (7–10)

7. Find the **Bonus %** for **IT** department.
8. Find the **Bonus %** for **Finance** department.
9. Calculate **Bonus Amount** for employee **E104**  
   (Bonus Amount = Salary × Bonus %).
10. If department is invalid, display **"No Bonus Data"**.

---

##  XLOOKUP Tasks (11–15)

11. Find **Salary** using `EmployeeID`.
12. Find **Department** using **Employee Name**.
13. Fetch **Location** of employee **Rohit Verma**.
14. If `EmployeeID = E999`, return **"Employee Not Found"**.
15. Find **Bonus %** using XLOOKUP from `Department_Bonus` (horizontal lookup).

---
