# prompt-injection-tester
# Prompt Injection Tester

A small tool that attacks a chatbot holding a secret and checks whether it leaks.

- Runs 8 common prompt injection attacks (ignore-instructions, role play, prompt leak, translation, encoding, fake authority, fiction)
- Compares a weak vs strong system prompt
- Gives a security score and lets you try your own attacks

Built with Streamlit and Gemini.

## Run locally
pip install -r requirements.txt
streamlit run app.py
