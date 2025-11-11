# Deloitte Forensic Technology Virtual Internship — Gender Pay Equality Analysis

## 📖 Overview
This project was completed as part of the **Deloitte Forensic Technology Virtual Internship** on Forage.  
It focuses on analyzing employee compensation data for **Daikibo Industrials** to detect potential **gender pay inequality** patterns.

The goal was to classify each job role’s *Equality Score* into clear categories, helping identify fairness or discrimination across factories and roles.

---

## 🎯 Objective
To classify employee equality scores into three distinct categories:

| Category | Condition (Equality Score) | Meaning |
|-----------|---------------------------|----------|
| **Fair** | Between -10 and +10 | Balanced pay between genders |
| **Unfair** | Between -20 and -10 OR between +10 and +20 | Noticeable imbalance |
| **Highly Discriminative** | Less than -20 or greater than +20 | Strong evidence of pay inequality |

---

## 🧩 Dataset
**File:** `Equality Table.xlsx`  

**Columns:**
- Factory  
- Job Role  
- Equality Score (integer; -100 to +100)  
- Equality Class (newly created column)

---

## ⚙️ Tools Used
- **Microsoft Excel**
- **Data Cleaning & Logical Classification (IF formulas)**
- **Basic Data Interpretation**

---

## 🧠 Steps Performed
1. Downloaded the provided Excel file: `Equality Table.xlsx`
2. Added a new column: **Equality Class**
3. Used Excel `IF` and nested `AND` functions to categorize equality scores
4. Verified correctness using multiple test values
5. Saved the final classified dataset for submission

---

## 📊 Outcome
Successfully classified each employee’s pay fairness level.  
The dataset now provides a clear snapshot of where gender pay inequality exists in Daikibo Industrials.

---

## 🧠 Skills Gained
- Data Cleaning & Classification in Excel  
- Logical Thinking (conditional formula design)  
- Practical understanding of pay equity metrics  

---

> 💡 *This project demonstrates practical data analysis logic applied to workplace fairness using simple yet powerful Excel techniques.*
