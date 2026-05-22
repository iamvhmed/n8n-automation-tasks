# 🚀 n8n Workflow: Daily Tasks to Email

Welcome to my n8n automation project! This workflow is designed to help you stay on top of your daily tasks by automatically fetching them from a Google Sheet and sending them directly to your email.

## ⚙️ How It Works
This workflow consists of 4 simple but powerful nodes:
1. **🕒 Schedule Trigger**: Set to run automatically every day at 19:49.
2. **📊 Google Sheets**: Connects to your "Daily Tasks" sheet and fetches the rows containing your to-dos.
3. **📦 Aggregate**: Groups the task data (Specifically the Task Number `#` and `Tasks` columns) into a single digestible format.
4. **📧 Gmail**: Formats the grouped data and sends a clean text email summarizing your tasks for the day.

## 🛠️ Setup Instructions
1. Copy the JSON workflow code.
2. Open your n8n instance and click **Import from Clipboard** (or paste directly into the canvas).
3. **Configure Credentials:**
   - Authenticate and connect your Google Sheets account.
   - Authenticate and connect your Gmail account.
4. Update the Google Sheets node with your specific `Sheet ID` and select the correct sheet (e.g., `Sheet1` or `الورقة1`).
5. Update the Gmail node with your target email address in the `Send To` field.
6. Activate the workflow and you're good to go!

## 💡 Use Case
Perfect for developers, students, or anyone who uses Google Sheets as a minimalist to-do list and wants a daily push notification via email to keep track of their goals.
