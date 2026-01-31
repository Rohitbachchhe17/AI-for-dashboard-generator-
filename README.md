# 📊 Data Analysis Graph Generator – n8n Workflow

This project is an automated **data analysis and reporting workflow built in n8n**.  
It reads student data from **Google Sheets**, generates multiple analytical charts, produces an **AI-generated insight summary**, and automatically sends a complete HTML report by email.

---

## 🚀 Features

- ✅ Automatic trigger from Google Sheets
- ✅ Data cleaning and preprocessing using JavaScript
- ✅ KPI calculation (department count, scholarship stats, averages)
- ✅ Automatic chart generation using QuickChart API
- ✅ AI-generated insight report using LLM
- ✅ Final HTML report creation
- ✅ Automated email delivery (Gmail)

---

## 🧠 What this workflow does

### 1️⃣ Google Sheets Trigger
The workflow automatically runs when the connected Google Sheet is updated.

---

### 2️⃣ Data Cleaning
Missing or empty values for important fields are normalized using JavaScript.

---

### 3️⃣ KPI & Aggregation Engine

The workflow computes:

- Student count by department
- Scholarship vs non-scholarship distribution
- Average GPA
- Average age
- Average attendance
- Gender distribution

---

### 4️⃣ Chart Generation

The workflow generates:

- 📊 Bar chart – students per department
- 📊 Bar chart – scholarship vs non-scholarship
- 🥧 Pie chart – scholarship distribution

All charts are created dynamically using **QuickChart API**.

---

### 5️⃣ AI Insight Generator

An AI agent analyzes the computed KPIs and produces a short professional report written for school leadership.

---

### 6️⃣ HTML Report Builder

All charts and the AI summary are merged into a single HTML report.

---

### 7️⃣ Email Automation

The final report is sent automatically using Gmail.

---

## 🛠️ Tech Stack

- n8n
- Google Sheets
- JavaScript (n8n Code nodes)
- QuickChart API
- Groq LLM
- Gmail API

---

## 📂 Project Files

```bash
Data analysis graph generator.json
README.md
