A lightweight Telegram chatbot built with aiogram and OpenAI’s ChatGPT API. This repository demonstrates a minimal, production-ready structure for a Telegram bot using environment configuration, optional Docker deployment, and clear developer documentation.
Features:
Telegram bot using aiogram
ChatGPT-style response generation via openai
Context-managed response memory
/start, /help, and /clear commands
.env configuration for secrets

Environment-> Python 3.8 conda create telebot -n python=3.8 -y
conda activate telebot
pip install -r requirements.txt
run-> python echo_bot.py