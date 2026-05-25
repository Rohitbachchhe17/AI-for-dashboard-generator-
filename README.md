# 📊 Data Analysis Graph Generator – n8n Workflow

This project is an automated **data analysis and reporting workflow built in n8n**.  
It reads student data from **Google Sheets**, generates multiple analytical charts, produces an **AI-generated insight summary**, and automatically sends a complete HTML report by email.

---
Full Demo Video is here : https://drive.google.com/file/d/16roDgLEW3_MDSZTLLswai8FWFdjZQNj-/view?usp=sharing

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3052cf14-74d4-4bdb-9b37-41986ee2e5f4" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b74ce854-5777-4fd1-aba7-a0f7c9fc4cfa" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2be7c43e-f4be-4848-b9e3-4432200c60f3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a4b3a0da-ad53-4cea-b942-6d8005ed1a80" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7f4d000a-c5b9-46c3-b290-ac460f8b1eb6" />


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
