# 🤖 AI-Agent-Meeting-Scheduler

This **n8n** workflow enables seamless meeting scheduling using natural language commands through **Telegram**. It supports both **text** and **voice messages**, automating the entire process from interpretation to calendar creation and email confirmation.

---

## 📌 Key Features

- **Message Type Detection**
  - Automatically distinguishes between text and voice inputs.

- **Voice-to-Text Transcription**
  - Transcribes voice messages using **OpenAI Whisper**.

- **Intelligent NLP Parsing**
  - Extracts meeting details such as:
    - 📅 Date
    - 🕒 Time
    - ⏳ Duration
    - 👤 Participant
    - 💬 Topic  
  - Powered by **OpenAI GPT**.

- **Google Calendar Integration**
  - Creates events directly in **Google Calendar** based on extracted details.

- **Email Confirmation**
  - Sends a confirmation email to the meeting participant.

- **Contact Lookup**
  - Uses **Google Sheets** to retrieve contact information.

- **Context Awareness**
  - Maintains memory for more natural, multi-turn conversations.

---

## 🛠 Built With

- [n8n](https://n8n.io/) – Low-code workflow automation
- [OpenAI Whisper](https://platform.openai.com/docs/guides/speech-to-text) – Voice transcription
- [OpenAI GPT](https://platform.openai.com/docs) – Natural Language Understanding
- [Google Calendar API](https://developers.google.com/calendar) – Event scheduling
- [Gmail API](https://developers.google.com/gmail/api) – Email confirmation
- [Google Sheets API](https://developers.google.com/sheets/api) – Contact retrieval

---

## 📥 Getting Started

1. Import the provided `.json` workflow into your n8n instance.
2. Connect your:
   - Telegram Bot
   - OpenAI API
   - Google Calendar & Gmail credentials
   - Google Sheets containing contacts
3. Deploy and test the workflow.

---

## 📧 Contact

Feel free to contribute or reach out for improvements!

---

