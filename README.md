# 📧 n8n Email Automation

An automated email delivery workflow built with **n8n** and **Gmail SMTP**, demonstrating scheduled email execution using the Wait node.

## 🛠️ Technologies

- n8n
- Gmail SMTP
- Wait Node
- Manual Trigger

## ⚙️ Workflow

The automation follows this sequence:

`Manual Trigger → Wait → Send an Email`

1. **Manual Trigger:** Starts the workflow manually.
2. **Wait Node:** Pauses execution until the configured date and time.
3. **Send an Email:** Automatically sends an email through Gmail SMTP.

## ✨ Features

- Scheduled email delivery.
- Execution at a specific date and time.
- Gmail SMTP integration.
- Automated email sending.
- Configurable waiting period.

## 🧪 Testing

The workflow was successfully tested.

**Result:** The email was received exactly at the scheduled time.

## 🎯 Project Goal

Develop practical workflow automation skills and understand how to integrate email services using n8n.

## 🚀 How to Use

1. Import the JSON workflow into n8n.
2. Configure your Gmail SMTP credentials.
3. Set the sender and recipient email addresses.
4. Configure a future date and time in the Wait node.
5. Execute the workflow manually.

**Note:** When running locally, keep n8n and your computer running until the scheduled execution is completed.

## 📌 Project Status

**Completed and tested successfully.**
