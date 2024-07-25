# TinderBot: Your Personal AI Assistant

Welcome to **TinderBot** — a Python bot that combines the convenience of *Telegram*, the power of *ChatGPT*, and the fun of *Tinder*. With TinderBot, you can create an attractive Tinder profile, generate interesting messages for dating, and even chat on your behalf.

## The Chatbot Can:
1. Generate a Tinder profile based on your description
2. Write interesting and intriguing messages for dating
3. Chat on your behalf
4. Practice conversations with the chatbot

## Useful Commands and Links:
1. `/start` — main menu of the bot
2. `/profile` — generate a Tinder profile
3. `/opener` — opening message for dating
4. `/message` — chat on your behalf
5. `/date` — chat with celebrities
6. `/gpt` — ask a question to the GPT chat

### Installation and Launch

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ezulex/TinderBolt.git
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate  # For Windows
    ```

3. **Install the necessary dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Create a `.env` file with your environment variables:**
    ```env
    TG_TOKEN="your_telegram_api_key"
    CHATGPT_TOKEN="your_openai_api_key"
    ```

5. **Launch the bot:**
    ```bash
    python main.py
    ```

### How to Use the Bot

After launching the bot, enter the `/start` command in Telegram to open the main menu. Then, use the commands to generate a profile, create messages, and chat. Enjoy the communication and let TinderBot help you find your match!

---
This project was created during the JavaRush Marathon. Learn more at [this link](https://javarush.com/groups/python-marathon).
