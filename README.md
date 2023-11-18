# telegram_bot

### install package 1st
Remember to install the telebot library if you haven't already by running:
```
pip install pyTelegramBotAPI
```

### Welcome message 

```
import telebot

TOKEN = "your_token_here"

bot = telebot.TeleBot(TOKEN)

@bot.message_handler(['start'])
def start(message):
    bot.reply_to(message, "Welcome To My Bot!")

bot.polling()
```

## 
TOKEN = "your_token_here" = type your bot api key here.

![image](https://github.com/masshuvo/telegram_bot/assets/108648096/87f6ae54-de46-46d7-a65e-1f4d32a0ed46)

