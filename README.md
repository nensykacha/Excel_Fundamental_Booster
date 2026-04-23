# 🚀 PR. 1 Fundamental Booster - Excel Project

This project is a comprehensive analytical tool designed to master Excel fundamentals and advanced dynamic data structures. It demonstrates the ability to manage complex datasets across multiple interconnected sheets.

## 📊 Project Architecture

The workbook is structured into **4 Primary Sheets**, each focusing on a distinct area of data management:

1. **❓ Question Sheet:** Contains the core project requirements and analytical objectives.
2. **🎓 Student Data:** Advanced academic tracking, grading systems, and **Dynamic Top-Performer Extraction**.
3. **💰 Sales Data:** Business finance management, tax logic, and financial rounding precision.
4. **👥 Employee Data:** HR management, service year calculations, and dynamic salary lookups.
5. **🧮 Calculation Sheet:** A centralized engine for complex formulas and backend data processing.

---

## 🛠️ Key Formulas & Logic Applied

### 1. Dynamic Extraction & Filtering
Used the advanced `FILTER` function to create a real-time list of top-performing students.
* **Logic:** Extracts students with a score **> 80%** from the Master Sheet to the Dashboard.
* **Formula:** `=FILTER('Student Data'!A2:I100, 'Student Data'!I2:I100 > 0.8)`

### 2. Lookup & Reference Mastery
* **VLOOKUP:** Implemented for seamless data retrieval across sheets based on unique IDs.
* **Cross-Sheet Referencing:** Established a dynamic link between the *Calculation Sheet* and *Master Data* sheets.

### 3. Financial & Math Precision
* **Rounding Logic:** Applied `ROUND`, `CEILING.MATH`, and `FLOOR.MATH` to manage currency and percentage accuracy in Sales data.
* **Date Analysis:** Utilized `DATEDIF` and `TODAY()` to calculate real-time employee experience and tenure.

### 4. Advanced Logical Classification
* **Nested IF & IFS:** Categorized performance tiers (Elite, Pro, Standard) based on multi-variable achievement scores.
* **IF with AND/OR:** Developed conditional triggers for discount eligibility and scholarship status.

---

## ⚠️ Compatibility Note
> **Note:** The dynamic `FILTER` function used in the Student Extraction module is exclusive to **Microsoft 365** and **Excel 2021**. This specific feature will not function in **Excel 2019** or older versions. For legacy support, Pivot Tables or Advanced Filters are recommended.

---

## 📂 Sheet Structure & Deliverables

| Sheet Name | Focus Area | Key Deliverables |
| :--- | :--- | :--- |
| **Student Data** | Academic Tracking | Grade Classification & Top Performer Extraction |
| **Sales Data** | Business Finance | Tax/Discount Logic & Rounding Precision |
| **Employee Data** | HR Management | Service Year Calculation & Salary Lookups |
| **Calculation** | Data Engine | Centralized Logic & Multi-Sheet Analysis |

---

**Project Developed by:** Nensy Kacha

**Technology:** Microsoft Excel (Office 365 / 2019)  
**Date:** April 2026
