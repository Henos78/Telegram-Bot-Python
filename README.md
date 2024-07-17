# Telegram-Bot-Python
This a telegram bot created by using python.

## How to Get Your Bot Token
To setup a chat bot first go telegram and search "### @BotFather" and follow these steps:
  1. Start a conversation with BotFather by clicking on the Start button.
  2. Type /newbot, and follow the prompts to set up a new bot.
  3. The BotFather will give you a token that you will use to authenticate your bot and grant it access to the Telegram API.
  ### Note: Make sure you store the token securely. Anyone with your token access can easily manipulate your bot.

## Setting Up the Coding Environment
For this bot we will be using the  pyTelegramBotAPI library. It is a simple but extensible Python implementation for the Telegram Bot API with both synchronous and asynchronous capabilities.

Install the pyTelegramBotAPI library using pip: (I am using macOs)
`pip3 install pyTelegramBotAPI`
create a .env file to store your token as below:
`export BOT_TOKEN=your-bot-token-here`
Run the source .env command to read the environment variables from the .env file.

Make sure to install the requests library for data scraping for the util.py file:
`pip3 install requests`

Feel free to make any new adjustments or modifications, hope you liked it, Cheers!
