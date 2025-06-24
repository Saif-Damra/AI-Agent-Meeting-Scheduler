# AI-Agent-Meeting-Scheduler

This workflow enables seamless meeting scheduling using natural language commands through Telegram. Whether a user sends a text or voice message, the system:

Detects message type (text or voice).

Transcribes voice messages using OpenAI Whisper.

Uses OpenAI GPT to extract meeting details: participant, date, time, duration, and topic.

Automatically creates a calendar event in Google Calendar.

Sends a confirmation email to the meeting participant.

Leverages Google Sheets for contact retrieval and integrates memory for context-aware conversations.

Built using n8n for low-code orchestration, OpenAI for natural language understanding, and Google APIs for scheduling and communication.
