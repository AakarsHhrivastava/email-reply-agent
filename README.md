# Email-reply-agent
AI-powered email reply agent built using n8n, Gemini, and Airtable. Automatically reads, understands, and replies to emails based on intent and context.

---

## 🚀 What It Does

- Listens for new emails via **Gmail Trigger**
- Parses the email body and metadata
- Uses **Gemini API** to understand tone, context, and intent
- Loads instructions from an XML config to personalize replies
- Sends the reply and stores it in **Airtable** for tracking

---

## 🧰 Tech Stack

- [n8n]– Workflow automation
- [Gemini Api] – AI model for reply generation
- [Airtable] – For storing replies + metadata
- [Gmail API} – To trigger on email received
- XML-based config – For flexible instruction loading

---

## 📸 Workflow Screenshot
![Screenshot 2025-06-22 231036](https://github.com/user-attachments/assets/cc98835f-da19-4a09-a579-c258ec0feb9e)
![Screenshot 2025-06-22 230102](https://github.com/user-attachments/assets/62a12b92-cbef-4862-a56f-7fb5bd131d1c)


---

## 📂 Files

- `email-reply-agent.json` – Exported n8n workflow
- `screenshot.png` – Visual representation of the flow

---

## 🛠 Setup Instructions

1. Import `email-reply-agent.json` into your n8n instance
2. Configure credentials for:
   - Gmail Trigger
   - Gemini (via API)
   - Airtable (API key)
3. Edit XML file if needed to change reply instructions
4. Deploy and let the agent respond to emails automatically!

---

## 🧠 Why It’s Useful

This agent saves time for SDRs, customer support, and anyone tired of writing repetitive emails. It ensures:
- Consistent tone and quality
- Faster response time
- Smart personalization

---

## 👤 Built By

**Aakarsh Shrivastava**  
[LinkedIn](https://www.linkedin.com/in/aakarsh-shrivastava-998bb21a0) 

---

