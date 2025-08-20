{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .AppleSystemUIFontMonospaced-Regular;}
{\colortbl;\red255\green255\blue255;\red214\green85\blue98;\red155\green162\blue177;\red81\green156\blue233;
}
{\*\expandedcolortbl;;\cssrgb\c87843\c42353\c45882;\cssrgb\c67059\c69804\c74902;\cssrgb\c38039\c68235\c93333;
}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f0\fs26 \cf2 # n8n Automations (Portfolio)\cf3 \
\
This repo contains two example automations built in **n8n** using mock data.  \
They demonstrate workflow automation, API integrations, and data enrichment.\
\
---\
\
\cf2 ## \uc0\u55357 \u56960  Automation 1: Form \u8594  Google Sheets \u8594  Gmail\cf3 \
**Flow:**\
\cf4 -\cf3  Trigger: On form submission  \
\cf4 -\cf3  Action: Append row in Google Sheets  \
\cf4 -\cf3  Action: Send email via Gmail  \
\
**Use case:**  \
Automatically record form responses in Google Sheets and notify stakeholders instantly by email.  }

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
