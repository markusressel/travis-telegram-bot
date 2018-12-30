# travis-telegram-bot
A travis config that can be used to send Telegram messages on new builds

![Telegram PR Message](/screenshots/Telegram PR Message.jpg)

# Usage
To use this 
* copy the `travis` folder and `.travis.yml` to your project (or add the required parameters to your existing config).
* add the required script parameters values to the TravisCI projec

## Script Parameters

| Name           | Description |
|---------------:|:------------|
| TELEGRAM_TOKEN | The token used to authenticate with the Telegram bot. |
| CHAT_ID        | The chat ID of the chat to send messages to. |

# Behaviour
The script send out a telegram message for every new PR build will inform
