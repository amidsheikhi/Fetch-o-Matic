# Fetch-o-Matic
Automated file downloader Telegram bot using n8n and direct link parsing
## 📦 Features

- Accepts valid direct download links
- Validates the URL using regex
- Downloads the file using HTTP Request
- Sends the file back to the user via Telegram

---

## 🔧 Setup Instructions

1. Clone the repo and open the project in n8n.
2. Replace the Telegram credentials in the `Telegram Trigger` and `Send File to User` nodes with your bot credentials.
3. Deploy the workflow on your n8n instance or n8n.cloud.
4. Add your bot to Telegram and test it by sending a direct file URL.

---

## 🛡️ Security

- ✅ No credentials or secrets are stored in this version.
- ✅ All webhook IDs and bot usernames are removed.
- ✅ Ready to publish or fork safely.

---

## 📁 Files

- `workflow.json`: Main n8n workflow (safe and sanitized)
- `.gitignore`: Ensures private files are not committed
- `README.md`: This file

---

## 📄 License

MIT License — free to use, modify, and distribute.


## 📥 Download the Workflow

You can download the workflow file here:  
➡️ [n8n-telegram-autodl-workflow.json](./n8n-telegram-autodl-workflow.json)

Add download link to n8n workflow



