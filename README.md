# 🚀 AI-Powered LinkedIn Auto-Publisher with n8n & Google Gemini

An automated end-to-end workflow built in **n8n** that monitors a Google Sheet, uses **Google Gemini AI** to write professional summaries/posts, and automatically publishes them to **LinkedIn**.

## 🔄 How It Works
1. **Google Sheets Trigger:** Watches your spreadsheet for any new rows or links.
2. **Google Gemini AI (Basic LLM Chain):** Reads the link/content and generates an engaging, well-structured post tailored for professional networks.
3. **LinkedIn Integration:** Automatically publishes the generated text straight to your LinkedIn profile.

---

## 🛠️ Tech Stack
* **No-Code Automation:** [n8n](https://n8n.io/)
* **Database:** Google Sheets
* **Generative AI:** Google Gemini
* **Social Media API:** LinkedIn API

---

## ⚙️ How to Use This Workflow
1. Download the `workflow.json` file from this repository.
2. Open your n8n instance, click **Workflows** -> **Import from File**, and upload the JSON.
3. Connect your own credentials for:
   * Google Sheets
   * Google Gemini (API Key)
   * LinkedIn Account
4. Update the Google Sheets Trigger node to point to your specific spreadsheet and column name.
5. Save and test your workflow!
