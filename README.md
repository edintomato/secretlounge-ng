secretlounge-ng
---------------
Rewrite of [secretlounge](https://github.com/6697/secretlounge), a bot to make an anonymous group chat on Telegram.

## Setup
```
$ pip3 install -r requirements.txt
$ cp conf.yaml.example config.yaml
Edit config.yaml with your favorite text editor.
$ ./secretlounge-ng
```

## @BotFather Setup
Message [https://t.me/BotFather](@BotFather) to configure your bot as follows:

* `/setprivacy`: enabled
* `/setjoingroups`: disabled
* `/setcommands`: paste the command list below

### Command list
```
start - Join the chat (start receiving messages)
stop - Leave the chat (stop receiving messages)
users - Get list of users
info - Get info about your account
motd - Show the welcome message
version - Get version & source code of this bot
modhelp - Show commands available to moderators
adminhelp - Show commands available to admins
toggledebug - Toggle debug mode (sends back all messages to you)
togglekarma - Toggle karma notifications
```