# 📊 Student Performance & Behavior Analysis Dashboard (Power BI)

## 📌 Project Overview

This project is a **comprehensive Power BI dashboard** designed to analyze **student academic performance, attendance, and behavior patterns**. The dashboard provides actionable insights for teachers, administrators, and stakeholders by combining multiple datasets into a single interactive report.

The project was created as part of a **Power BI Practical / Academic Assignment**, focusing on **Data Modeling, DAX, Visualization, and Interactivity**.

---

## 🎯 Objectives

* Analyze **student performance** across subjects, classes, and terms
* Monitor **attendance trends** and overall attendance percentage
* Understand **behavior distribution** (Positive / Negative / Neutral)
* Classify students into **High / Medium / Low performance categories**
* Build an **interactive and user-friendly Power BI report**

---

## 🗂️ Datasets Used

The project uses the following datasets (Excel files):

| Dataset         | Description                                           | Link                        |
| --------------- | ----------------------------------------------------- | --------------------------- |
| Students.xlsx   | Student master data (StudentID, Name, Class, Section) | [Download](Students.xlsx)   |
| Scores.xlsx     | Subject-wise student scores and max scores            | [Download](Scores.xlsx)     |
| Attendance.xlsx | Student attendance records                            | [Download](Attendance.xlsx) |
| Behavior.xlsx   | Student behavior records by type                      | [Download](Behavior.xlsx)   |

> 🔗 **Note:** All datasets are connected using `StudentID` as the primary key.

---

## 🧹 Data Modeling & Cleaning

* Loaded all datasets into **Power BI Desktop**
* Cleaned column names (removed spaces, standardized naming)
* Corrected data types (numeric, text, percentage)
* Handled missing/null values where appropriate
* Created **one-to-many relationships** between Students and other tables

---

## 🧠 DAX Measures Implemented

Key DAX measures used in this project:

* **% Score** = Score / MaxScore
* **Average Score per Subject**
* **Attendance %** (calculated based on attendance records)
* **Behavior Count per Type**
* **Performance Category** (High / Medium / Low using SWITCH logic)

These measures enable dynamic filtering and real-time calculations across visuals.

---

## 📈 Visualizations Included

The dashboard includes the following visuals:

### 📊 Charts

* **Bar Chart:** Average Scores by Subject and Class
* **Line Chart:** Performance Trend by Term
* **Donut Chart:** Behavior Types Distribution

### 📋 Tables

* **Student-wise score table** with conditional formatting:

  * 🟢 Green for scores > 80%
  * 🔴 Red for scores < 40%

### 🧾 KPI Cards

* Total Students
* Average Attendance %
* Overall Average Score

---

## 🧩 Interactivity Features

* **Slicers:** Class, Section, Subject, Term
* **Drillthrough Page:** Individual student profile view
* **Tooltips:** Mini metrics on hover
* **Bookmark Navigation:** Switch between Academic and Behavioral views

---

## 📱 Mobile Optimization (Optional)

* Mobile layout created for Power BI Mobile App
* Optimized card and chart placement for small screens

---

## 🖼️ Screenshots

Below are sample screenshots of the dashboard:

* Dashboard Overview: [View Screenshot](Screenshot_Overview.png)
* Academic Performance View: [View Screenshot](Screenshot_Academic.png)
* Behavioral Analysis View: [View Screenshot](Screenshot_Behavior.png)

> 📌 *Screenshots can be found in the project folder or repository.*

---

## 📦 Deliverables

* ✅ Power BI file: **Power bi practical exam.pbix**
* ✅ Excel datasets
* ✅ README.md documentation

---

## 🚀 How to Use

1. Download all datasets and the `.pbix` file
2. Open the `.pbix` file in **Power BI Desktop**
3. Refresh data if required
4. Use slicers and visuals to explore insights

---

## 🧑‍🎓 Learning Outcomes

* Hands-on experience with **Power BI data modeling**
* Practical use of **DAX measures and SWITCH logic**
* Building **interactive dashboards**
* Applying **conditional formatting and drillthrough**

---

## ✨ Conclusion

This project demonstrates an end-to-end Power BI solution for analyzing student data. It highlights how raw data can be transformed into **meaningful insights** using effective modeling, DAX, and visualization techniques.

---

### 🔖 Author

**Created by:** *[Janki Dholariya]*
**Tool Used:** Power BI Desktop
**Project Type:** Academic / Practical Assignment

---

⭐ *If you like this project, feel free to give it a star and share feedback!*
