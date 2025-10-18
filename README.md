# AIExpenseManager
This Repo Contains The AI Expense Manager Workflow

# 💰 AI-Driven Expense Manager Workflow

> **An automated financial management system** that tracks company expenses, generates weekly and monthly summaries, and provides insights through an integrated AI chatbot — **TeleBot**.

---

## 🧩 Overview

The **AI Expense Manager Workflow** automates the entire company expense management process using **Google Sheets, Supabase, Slack, Gmail**, and **AI automation**.  
It provides:
- Weekly & monthly expense summaries for each **department**
- Consolidated financial reports for the **CEO**
- Real-time insights through an interactive **Telegram chatbot**

This workflow is designed to streamline financial reporting and reduce the manual work of compiling reports or analyzing spending trends.

---

## 🚀 Features

✅ **Automated Weekly & Monthly Summaries** — Sends detailed expense reports to each department and the CEO  
✅ **Slack Notifications** — Posts automated updates in Slack channels for transparency  
✅ **AI-Powered Chatbot (TeleBot)** — Query company financials directly through Telegram  
✅ **Data Management Automation** — Automatically resets monthly sheets and archives data to a raw data sheet  
✅ **Dynamic Insights** — Detects top spending departments, trends, and notable financial highlights  

---

## 🧠 How It Works

### 🗓️ Step 1 — Data Input
- Financial data is entered into **Google Sheets** for each expense:
  - Date  
  - Category  
  - Description  
  - Amount  

Weekly boundaries are marked by lines for easier tracking.

---

### ⚙️ Step 2 — Weekly Workflow Trigger

1. **CEO Summary Trigger**
   - Generates a **weekly summary email** for the CEO containing:
     - Total weekly spending  
     - Top departments & categories  
     - Notable highlights  
     - Summary insights  
   - Sends the same update in the CEO’s **Slack channel**

2. **Department Summaries Trigger**
   - Each department (Sales, IT, Marketing, HR, Operations) receives a personalized email report:
     - Weekly total spending  
     - Expense breakdowns  
     - Key highlights  
     - Department summary reflection  

---

### 📅 Step 3 — Monthly Workflow Trigger

1. **CEO Monthly Summary**
   - Consolidates all weekly data into a full monthly financial report:
     - Total monthly spending  
     - Spending trends across weeks  
     - Top categories  
     - Summary & reflection section  
   - Shared via **email and Slack**

2. **Department Monthly Summaries**
   - Each department receives a detailed monthly financial email showing:
     - Overview  
     - Top categories  
     - Notable highlights  
     - Summary & reflection  

---

### 🗄️ Step 4 — Data Reset & Archiving
- At the end of each month:
  - The main **Google Sheet** (used for active data) is **reset automatically**.  
  - All monthly expense data is transferred to a **Raw Data Sheet** for permanent record keeping.
- This keeps the working sheet clean while preserving historical data for analytics.

---

### 💬 Step 5 — Chatbot: TeleBot (AI Finance Assistant)
The integrated **Telegram chatbot** (“TeleBot”) allows interactive access to financial data.

#### Example Conversations
> 👤 **You:** Which department had the highest expenses this month?  
> 🤖 **TeleBot:** The *Operations/Admin* department incurred the most expenses due to rent, utilities, and staff salaries.

> 👤 **You:** Which week had the most expenses?  
> 🤖 **TeleBot:** The week of *September 1–7* had the highest expenses (₨451,000) driven by laptop purchases and IT marketing campaigns.

TeleBot reads from the **raw data sheet** and uses AI logic to summarize and respond naturally.

---

## 📊 Data Flow Diagram

```plaintext
Google Sheets (Weekly + Monthly Data)
        ↓
   Workflow Triggers
        ↓
  CEO & Department Summaries
        ↓
   Slack + Gmail Updates
        ↓
  Raw Data Archive (Monthly)
        ↓
      TeleBot Access
