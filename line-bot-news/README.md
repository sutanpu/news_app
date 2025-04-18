# 📰 LINE Bot News Summarizer (with AI-style Summary)

This is a Python app that lets you send messages to a LINE Bot and get an "AI-style" summary of the latest news in return.

> ⚠️ Currently, the ChatGPT API response is mocked (dummy) to enable local development **without API charges**.

---

## 🧠 Features

- ✅ AI-style summary of messages sent via LINE (dummy response)
- ✅ Flask-based Webhook server
- ✅ LINE Messaging API integration
- ✅ Exposed local server via ngrok
- ✅ API key management with `.env` for secure development

---

## 📸 Demo Screenshot

> Message: `Tell me some interesting news`

![LINEapp](https://github.com/user-attachments/assets/9c38cee7-cb84-4529-8bc2-b87a3191476c)


---

## 🧰 Tech Stack

| Item         | Description                        |
|--------------|------------------------------------|
| Language     | Python                             |
| Libraries    | Flask, line-bot-sdk, python-dotenv |
| External API | LINE Messaging API                 |
| Tools        | ngrok, VSCode                      |

---

## 📁 Project Structure

```bash
line-bot-news/
├── app.py               # Flask app (handles LINE + OpenAI logic)
├── .env                # Environment variables (e.g., API keys)
├── requirements.txt     # Python dependencies
└── README_EN.md         # This file![LINEapp](https://github.com/user-attachments/assets/78781558-4a65-47a0-b75c-5231b8857d6e)

