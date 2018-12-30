# travis-telegram-bot
A travis config that can be used to send Telegram messages on new builds

<img src="/screenshots/telegram_pr_message.jpg" alt="Telegram PR Message" width="270" height="585">

# Usage
To use this: 

## Copy files
Copy the `travis` folder and `.travis.yml` to your project (or add the required parameters to your existing config).

## Environment Variables
Now add the required script parameters values to the TravisCI project's settings page of the project you want to use travis-telegram-bot on:

<img src="/screenshots/travis_environment_variables.png" alt="Telegram PR Message">

### Script Parameters

| Name           | Description |
|---------------:|:------------|
| TELEGRAM_TOKEN | The token used to authenticate with the Telegram bot. |
| CHAT_ID        | The chat ID of the chat to send messages to. |

## Create a PR
Your next PR will build an APK and send it to you via telegram.
