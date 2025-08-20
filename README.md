# n8n Automations (Portfolio)

This repo contains two example automations built in **n8n** using mock data.  
They demonstrate workflow automation, API integrations, and data enrichment.

---

## 🚀 Automation 1: Form → Google Sheets → Gmail
**Flow:**
- Trigger: On form submission  
- Action: Append row in Google Sheets  
- Action: Send email via Gmail  

**Use case:**  
Automatically record form responses in Google Sheets and notify stakeholders instantly by email.  

## 🚀 Automation 2: Data Enrichment with APIs
**Flow:**
- Trigger: Manual execution  
- Action: Get rows from Google Sheets  
- Action: Call external APIs  
  - Genderize (predict gender)  
  - Nationalize (predict nationality)  
  - Agify (predict age)  
- Action: Append/Update row in Google Sheets  
- Action: Send email via Gmail  

**Use case:**  
Enrich existing data with predictions and insights, store results back in Sheets, and send a summary email.  
