# AIExpenseManager
This Repo Contains The AI Expense Manager Workflow

# 📊 Expense Manager Workflow Demo

## Overview

In this project, I built an **automated expense management workflow** for a company’s financial data.  
It tracks all expenses from Google Sheets, generates **weekly and monthly summaries** for the **CEO and each department**,  
and even includes a **Telegram chatbot** for querying insights from the data.

Watch The Video: (https://vimeo.com/1131609819)

---

## ⚙️ Features

- **Google Sheets Integration** – Store all weekly and monthly financial entries.
- **Automated Summaries**
  - **Weekly summaries** for the CEO and each department.
  - **Monthly summaries** for the CEO and each department.
- **Email + Slack Notifications**
  - Each summary is automatically sent via **Gmail** to the CEO and departments.
  - Summaries are also posted automatically in the **Slack channel**.
- **Data Archiving**
  - At the end of each month, the data from the main sheet is automatically reset.
  - All past records are moved to a **Raw Data Sheet** for long-term storage.
- **Telegram Chatbot ("TellyBot")**
  - Interact with your company’s financial data using natural language.
  - Ask questions like:
    - “Which department had the most expenses?”
    - “Which week had the highest spending?”
  - The bot responds with detailed insights from the raw data.

---

## 🧩 Workflow Example

1. Fill the company’s weekly expenses in Google Sheets.
2. Trigger the **weekly summary flow**:
   - Sends weekly summaries to the CEO and each department.
   - Posts summary messages in Slack.
3. At the end of the month, trigger the **monthly summary flow**:
   - Generates full-month summaries for the CEO and departments.
   - Sends emails with detailed breakdowns.
4. Data is automatically reset in the main sheet and moved to the raw data sheet.
5. Use **TellyBot** to chat with the financial data for quick insights.

---

## 💬 Example Chatbot Interaction

**You:** Which department spent the most this month?  
**TellyBot:** The Operations & Admin department incurred the most expenses this month due to rent, utilities, and staff salaries.

**You:** Which week had the highest spending?  
**TellyBot:** The week of September 1st to 7th had the highest total (₨451,000) mainly due to laptop purchases and IT marketing campaigns.

---

## 🏁 Summary

This workflow demonstrates how a company’s expense management can be **fully automated** —  
from data entry and analytics to reporting and communication — using Google Sheets, Gmail, Slack,  
and a Telegram bot for seamless interaction.

Authur
AbdulRehman (Solo)
Abdulrehman657.pk@gmail.com

