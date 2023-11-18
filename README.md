# telegram_bot
## I will be programming the Telegram bot entirely using the Python programming language.So you must have Python 3 installed on your system and have variables setup with scripts.
![image](https://github.com/masshuvo/telegram_bot/assets/108648096/93407d53-e5c1-4954-906d-86a992d6f67c)
</br> 
</br> path then enter:

</br>
</br>

![image](https://github.com/masshuvo/telegram_bot/assets/108648096/f4d09e0c-515c-4b96-bd91-97442496a9eb)
</br>

1st line : 
```
C:\Program Files\Python312\
```
2nd line :
```
C:\Program Files\Python312\Scripts\
```
then save : This location must be the address where your first Python programming is installed on your computer.
like this : 

![image](https://github.com/masshuvo/telegram_bot/assets/108648096/c3060206-9313-4ea5-a701-b7be12e0e304)



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

