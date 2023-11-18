# telegram_bot
## I will be programming the Telegram bot entirely using the Python programming language.So you must have Python 3 installed on your system and have variables setup with scripts.

error like this : WARNING: The script normalizer.exe is installed in 'C:\Users\M.A.S SHUVO\AppData\Roaming\Python\Python312\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location. 
</br>
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


-------------------------------------------------------

# if you run this script with your rooted Android device like ::
## Kali Nethunter 
## Termux 
## Stryker 
## Any Terminal 

I'm showing example for Kali Nethunter 


First you must have Python 3 installed on your system: 
```
apt install python3 -y
```
Then you create a specific folder & go to their: 

```
mkdir telegram_bot; cd telegram_bot
```
open any tax editor like this: 
```
nano tele.py
```

Past this Code: You need to insert here your API token;

```
import telebot

TOKEN = "5696027935:AAFyWiQNwLMcnkdFO95ak9xK5gsS8Y0"

bot = telebot.TeleBot(TOKEN)

@bot.message_handler(['start'])
def start(message):
    bot.reply_to(message, "Welcome To My Bot!")

bot.polling()
```

Then give it execute permission:
```
chmod +x tele.py
```

This package must be installed: 
If it is not installed then you can install it by executing this command

```
pip install pyTelegramBotAPI
```

![Screenshot_2023-11-18-23-07-05-426_com offsec nhterm](https://github.com/masshuvo/telegram_bot/assets/108648096/0519f4e5-6d1d-418f-9cfe-385c92994723)


If everything is correct now run:

```
python3 tele.py
```

![Screenshot_2023-11-18-23-16-01-218_org telegram messenger web](https://github.com/masshuvo/telegram_bot/assets/108648096/2b895357-5ab4-47fd-a96b-331406c9e098)

I tested it myself and found it working on my system. I have included a screenshot as an example.
