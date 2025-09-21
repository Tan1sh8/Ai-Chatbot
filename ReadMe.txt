=========================
🤖 ChatGPT Discord Bot
=========================

📄 ABOUT:
This is a Discord chatbot written in Python that uses the OpenRouter API to generate AI responses.
It works only in the channel where it's set up using the `-ai setup` command.

✅ Features:
- User specific memory
- Typing indicator
- Channel lock/unlock setup
- Simple prefix commands

=========================
📁 PROJECT FILES:
=========================

1. bot.py           → Main Python script that runs the bot.
2. config.json      → Configuration file (API key, model, and settings).
3. requirements.txt → Python dependencies for Katabump or local hosting.

=========================
⚙️ SETUP INSTRUCTIONS:
=========================

🔸 STEP 1: Edit `config.json`

# Open the `config.json` file and update the following:
- `"api_key"`: Replace with your OpenRouter API key (line 2)
- `"system_context"`: Customize the assistant personality (line 4)
- `"error_message"`: Change the fallback message shown on error (line 5)

🔸 STEP 2: Edit `bot.py`
- At the bottom, replace `<YOUR_BOT_TOKEN>` with your Bot Token.

🔻 STATUS : (bot.py line 35-36) 
- status=discord.Status.online # Options: online, idle, dnd, invisible
- activity=discord...., name="<YOUR_STATUS_MESSAGE>"), #enjoyy!!!