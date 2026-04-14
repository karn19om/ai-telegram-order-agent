# AI Order Management Agent

### (Telegram + n8n + AI + Excel Automation)

---

##  Project Overview

This project is an **AI-powered order management system** that automates customer interaction and inventory handling using a Telegram bot.

The system is built using **n8n workflow automation** and integrates AI to intelligently respond to user queries and FAQs.

---

##  Key Features

* 📩 **Order Collection via Telegram**
  Users can place orders directly through a Telegram bot

* 📊 **Automatic Excel Update**
  Orders and inventory are stored and updated in Excel

* 📦 **Inventory Management**
  Keeps track of product availability

* ❓ **AI-based FAQ Handling**
  Answers user queries using AI

* 🔄 **Fully Automated Workflow**
  No manual intervention required

---

## ⚙️ Tech Stack

* n8n (Workflow Automation)
* Telegram Bot API
* OpenAI API
* Excel / Google Sheets

---

## 🔄 Workflow Architecture

```text
User (Telegram)
      ↓
Telegram Trigger (n8n)
      ↓
AI Processing (OpenAI)
      ↓
Excel Update (Orders / Inventory)
      ↓
Response to User
```

---

## 📂 Project Structure

```
ai-telegram-order-agent/
│
├── workflow.json        # n8n exported workflow
├── README.md            # Project documentation
├── screenshots/         # Project screenshots
```

---

## 🛠️ Setup Instructions

1. Install n8n locally or use cloud version
2. Import `workflow.json` into n8n
3. Configure credentials:

   * Telegram Bot Token
   * OpenAI API Key
4. Connect Excel / Google Sheets
5. Activate the workflow

---


---

## 🎯 Future Improvements

* 💳 Payment integration
* 📈 Dashboard analytics
* ☁️ Cloud deployment
* 🧠 Advanced AI memory

---

OM NARAYAN
---

## 🌟 Acknowledgements

* n8n for workflow automation
* OpenAI for AI capabilities
* Telegram Bot API

---

---
