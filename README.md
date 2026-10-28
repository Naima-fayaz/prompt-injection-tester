# Prompt Injection Challenge

A practice game for learning prompt injection. Each level has a chatbot guarding a fake secret code.
Write your own attack prompt and try to make it leak the code.

- 3 levels: Weak, Medium, Strong (Strong adds an output filter)
- Limited attempts per session, hints available
- Built with Streamlit and Gemini Flash-Lite
- API key is read from server-side secrets only, never shown in the app

## Run locally
pip install -r requirements.txt
set GEMINI_API_KEY=your_key   (Windows)  /  export GEMINI_API_KEY=your_key  (Mac/Linux)
streamlit run app.py

For Streamlit Cloud: App Settings > Secrets > GEMINI_API_KEY = "your key"
