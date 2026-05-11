# 📊 HR Analytics Dashboard | Employee Attrition Insights

<img width="1356" height="731" alt="Screenshot 2026-05-10 184228" src="https://github.com/user-attachments/assets/f4a41633-0df9-4a1c-9138-c85d44f27ca6" />

-------

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-FFB600?style=for-the-badge&logo=microsoft&logoColor=white)

> **"22.47% attrition rate analyzed across 10,000+ employees — uncovering key drivers of employee turnover and actionable retention strategies."**

---

## 📌 Project Overview

This project delivers an **interactive HR Analytics Dashboard** built with **Power BI**, using a comprehensive **HR Attrition dataset** (10,000 employees, 22+ attributes). The dashboard provides **actionable insights** into:

- ✅ **Attrition Rate** (22.47%)  
- ✅ **Department-wise & Role-wise attrition**  
- ✅ **Impact of Overtime, Business Travel, and Salary Hike**  
- ✅ **Job Satisfaction & Environment Satisfaction trends**  
- ✅ **Distance from Home & Tenure-based attrition patterns**

The goal is to help HR leaders and business stakeholders **reduce unwanted attrition**, improve retention strategies, and optimize workforce planning.

---

## 🎯 Key Performance Indicators (KPIs)

| KPI | Value |
|-----|-------|
| 👥 **Total Employees** | 10,000 |
| ❌ **Total Attrition** | 2,247 |
| ✅ **Active Employees** | 7,753 |
| 📉 **Attrition Rate** | **22.47%** |
| 📅 **Average Age** | 40 years |

---

## 📸 Dashboard Preview

![Dashboard Overview](./Images/dashboard_preview.png)  
*[Replace with actual screenshot of your Power BI dashboard]*

---

## 🧩 Key Insights from the Dashboard

### 1️⃣ Attrition by Department
- 🟢 **Data Science** – 442 (20%)
- 🔵 **IT Services** – 430 (19%)
- 🟠 **Network Administration** – 410 (18%)
- 🟣 **Software Development** – 462 (21%)
- 🟡 **Cyber Security** – 503 (22%)

### 2️⃣ Attrition by Business Travel
- ✈️ **Travel Frequently** – 1,182 (52.6%)
- 🚗 **Travel Rarely** – Significant contributor
- 🏠 **No Travel** – 375 (16.7%)

### 3️⃣ Attrition by Overtime
- ⏰ **Overtime = Yes** – 798 (36%)
- ✅ **Overtime = No** – 1,449 (64%)

> 💡 *Employees working overtime show significantly higher attrition rates.*

### 4️⃣ Job Satisfaction Distribution
| Rating | Count |
|--------|-------|
| ⭐ 1 (Very Low) | 545 |
| ⭐⭐ 2 (Low) | 541 |
| ⭐⭐⭐ 3 (Medium) | 402 |
| ⭐⭐⭐⭐ 4 (High) | 397 |
| ⭐⭐⭐⭐⭐ 5 (Very High) | 362 |

### 5️⃣ Top 5 Roles with Highest Attrition
| Job Role | Attrition Count |
|----------|----------------|
| Consultant | 198 |
| Director | 181 |
| Software Engineer | 181 |
| Technical Lead | 179 |
| Business Analyst | 177 |

---

## 📁 Dataset Structure

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `Employee_ID` | INT | Unique employee identifier (Primary Key) |
| `Age` | INT | Employee age |
| `Attrition` | VARCHAR(3) | Yes / No |
| `Department` | VARCHAR(30) | Department name |
| `Job_Role` | VARCHAR(30) | Specific role |
| `Salary` | INT | Annual salary |
| `Overtime` | VARCHAR(3) | Yes / No |
| `Job_Satisfaction` | INT | 1–5 scale |
| `Years_since_last_promotion` | INT | Years since last promotion |
| ...and 13 more attributes | ... | Complete HR profile |

> 📥 **Source:** Synthetic HR dataset simulating real-world employee data.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=power-bi&logoColor=black) | Dashboard creation & visualization |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) | Data storage & SQL queries |
| ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Data extraction & transformation |
| ![DAX](https://img.shields.io/badge/DAX-FFB600?style=flat-square&logo=microsoft&logoColor=black) | Measures & calculated columns |
| ![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=flat-square&logo=microsoft&logoColor=white) | Data cleaning & transformation |

---

## 🚀 How to Use This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/HR-Attrition-Analytics-Dashboard.git
