# Gemini & Groq Conversational Python Project

This Python project demonstrates a conversation between two AI models: **Gemini** (`gemini-2.5-pro`) and **Groq** (`openai/gptoss-120b`) using the OpenAI library. Each model has a distinct personality: Gemini provides snarky replies, while Groq is polite. The models interact with each other in a 5-turn conversation.

---

## Features

- Calls **Gemini** and **Groq** models via API.
- Configurable personalities for AI models.
- Facilitates a multi-turn conversation between models.

---

## Setup

1. **Get API keys**:

   - **Google Gemini API**: [https://ai.google.dev/gemini-api/docs](https://ai.google.dev/gemini-api/docs)  
   - **Groq API**: [https://console.groq.com/home](https://console.groq.com/home)  

2. **Save API keys** in a `.env` file at the root of the project:

   ```env
   GOOGLE_API_KEY=your_google_api_key_here
   GROQ_API_KEY=your_groq_api_key_here
   ```

---

## Endpoints

- **Gemini**:

  ```python
  gemini_url = "https://generativelanguage.googleapis.com/v1beta/openai/"
  ```

- **Groq**:

  ```python
  groq_url = "https://api.groq.com/openai/v1"
  ```


   ```

The models will converse with each other **5 times**, displaying snarky and polite responses.



## Notes

- Gemini is configured for **snarky replies**.
- Groq is configured for **polite replies**.
- Ensure your `.env` file is **not committed to version control** to keep API keys secure.

---

