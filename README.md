Expense Tracker Bot

Overview
Manage daily personal finances quickly without opening heavy budgeting applications. This Telegram bot stores your spending securely in SQLite and generates instant monthly summaries.

Features
- Quick expense logging via simple text messages
- Categorize spending automatically by category input
- Monthly summary reports grouped by category

Local Setup
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Copy .env.example to .env and insert your Telegram bot token
4. Run python main.py

Cloud Deployment
Deploy easily on Render or Koyeb using the standard Python buildpack. Set the start command to python main.py and configure the BOT_TOKEN environment variable.
