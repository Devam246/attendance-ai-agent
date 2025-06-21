# Attendance Analyzer AI Agent 🧠
An LLM-powered autonomous agent that analyzes daily biometric attendance data, updates a live Google Sheet calendar, and allows HR to query real-time insights through a Telegram chatbot.


An autonomous AI-powered agent that:
- Analyzes biometric attendance data from CSV or live feeds
- Uses Azure GPT-4o to answer HR queries intelligently
- Operates via a Telegram bot interface
- Reads and updates attendance data into a Google Sheet
- Sends automated email notifications to HR and employees

---

## Features

-  LLM-powered HR Q&A via Telegram
-  Absence and late detection based on defined rules
-  Calendar-style Google Sheet attendance view
-  Color-coded status (Present, Late, Absent, etc.)
-  Email notifications to HR/employees
-  Natural language attendance summaries 

---

## Tech Stack

| Component       | Tool / API                  |
|----------------|-----------------------------|
| LLM             | Azure OpenAI GPT-4o         |
| Sheet Backend   | Google Sheets API           |
| Interface       | Telegram Bot (`python-telegram-bot`) |
| Logic & Parsing | Python, Pandas              |
| Emails (optional)| Gmail SMTP     |

---

