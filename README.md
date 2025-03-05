# Net Salary Calculator, Sorting Names, and Memory Management

## Overview
This project contains three C programs that solve different problems related to salary calculations, sorting names, and dynamic memory management. The programs were first written on an **online C compiler** before being pushed to **GitHub**.

## Team Members
- **Kellia Muzira**: Implemented **Question 3** (Memory Management) and wrote this **README file**.
- **Aubin Saiba**: Implemented **Question 1** (Net Salary Calculator) and **Question 2** (Sorting Names).

## Program Descriptions
### 1. Net Salary Calculator
**Filename:** `net_salary_calculator.c`
**Contributor:** Aubin Saiba

This program calculates the **net salary** of an employee based on the **gross salary** and several deductions:
- **Tax on salary** (based on salary range)
- **Medical insurance** (5%)
- **Maternity leave** (0.3%)
- **Social security fund** (3%)

Each deduction is implemented as a **separate function** that uses **pointers** to manipulate the salary. The net salary is then printed to the user.

### 2. Sorting Names (Bubble Sort)
**Filename:** `sorting_names.c`
**Contributor:** Aubin Saiba

This program sorts a **list of 20 names** in either:
- **Ascending order (A-Z)**
- **Descending order (Z-A)**

The user is prompted to enter either `asc` or `desc`, and the names are sorted using **Bubble Sort** before being displayed.

### 3. Memory Management (Storing Student Emails)
**Filename:** `memory_management.c`
**Contributor:** Kellia Muzira

This program dynamically stores the **email addresses** of **10 students** in an array using **malloc()**. Then, it demonstrates **shrinking memory** by reducing the array to **6 students** using **realloc()**. Finally, the program frees all allocated memory to avoid memory leaks.


## Advantages of Using Pointers in Question 1
Using **pointers** in the Net Salary Calculator provides several benefits:
- **Memory Efficiency**: Modifies values directly without creating extra copies.
- **Faster Execution**: Avoids passing large amounts of data by reference.
- **Code Flexibility**: Allows functions to modify variables outside their scope.

## Contributions Summary
| Question | Topic | Contributor |
|----------|-----------------------------|----------------|
| 1 | Net Salary Calculator | Aubin Saiba |
| 2 | Sorting Names (Bubble Sort) | Aubin Saiba |
| 3 | Memory Management | Kellia Muzira |
| - | README Documentation | Kellia Muzira |

## Repository Link
[GitHub Repository](<https://github.com/Mkellia/wk9assignment.git>)

---
**Maintained by:** Kellia Muzira & Aubin Saiba


