# 📊 Recruitment Drop-Off Prediction System

## 🚀 Project Overview
This project is an AI-powered recruitment automation system that helps HR teams identify candidates who are likely to drop out during the hiring process.

It uses:
- n8n (Automation)
- Google Sheets (Data Source)
- Gmail API (Communication)
- Power BI (Dashboard Visualization)

---

## 🎯 Problem Statement
Recruiters face challenges like:
- Candidate drop-offs
- Delayed hiring
- High recruitment costs

This system predicts high-risk candidates and helps HR take timely actions.

---

## ⚙️ Workflow (n8n Automation)
1. Data is collected via Google Forms → stored in Google Sheets  
2. n8n workflow triggers when new data is added  
3. System checks **Days Since Last Contact**
   - >4 days → High Risk  
   - >2 days → Medium Risk  
   - Else → Low Risk  
4. Risk level is assigned automatically  
5. Data is stored in processed sheet  
6. Emails are sent:
   - Candidate update email  
   - HR alert for risky candidates  

---

## 📊 Dashboard (Power BI)
The dashboard includes:
- Total Candidates
- High Risk Candidates
- Risk Distribution
- Drop-off Analysis
- Role-wise applications

---

## 🛠️ Tools & Technologies
- n8n (Workflow Automation)
- Google Sheets
- Gmail API
- Power BI
- AI Tools (ChatGPT, Gemini)

---

## 📁 Project Files
- n8n Workflow JSON
- Candidate Dataset
- Power BI Dashboard

---

## 💡 Key Features
- Automated candidate tracking
- Risk prediction system
- Email alerts for HR
- Data visualization dashboard

---

## 📌 Future Improvements
- Integration with ATS systems
- Machine Learning model for prediction
- Real-time notifications

---

## 👩‍💻 Author
Akanksha
