# WHOIS Telegram Bot
## installation
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Abhijith-cloud/WHOIS-Telegram-Bot/)
```sh
$ git clone https://github.com/Abhijith-cloud/WHOIS-Telegram-Bot.git / gh repo clone Abhijith-cloud/WHOIS-Telegram-Bot
```
```sh
$ pip3 install -r requirements.txt
```
### Add your bot details

An example `config.py` file could be:

```python3
class TeleInfo():
    API_ID = 1234567 #Add your API_ID from https://my.telegram.org/apps
    API_HASH = 'bc4811980930ad49d7f8e2b024f7cf13' #Add your Bot token from @Botfather
    BOT_TOKEN = '1991308069:tU1gaAyvgAAGgo3F2AI2J7nxcqvkwoTCrpY' #add your API_HASH from https://my.telegram.org/apps
```

Go and get the bot token [@BotFather](https://telegram.dog/BotFather)

click the link to get your app id & api_hash [my.telegram.org](https://my.telegram.org/auth)

### Run your Bot

```sh
$ python3 -m bot
```

## Credits, and Thanks to

* [Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)

#### LICENSE
- GPLv3
