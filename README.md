# Copyright Protection Bot

This Telegram bot helps protect your group from copyright infringement by automatically deleting predefined messages or messages containing specific keywords.

## Features

- Deletes predefined messages or messages containing specified keywords.
- Logs when the bot is started.
- Deletes edited messages.
- Provides introduction and support group links.

## Deployment

You can deploy this bot to Heroku with one click using the button below:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/MrH4CK3474/BAD-COPYRIGHT-)

Before deploying, make sure you have the following information ready:
- Telegram bot token
- Support group link
- Logs group link
- Owner's Telegram ID

Once deployed, set these environment variables in your Heroku app:
- `BOT_TOKEN`: Your Telegram bot token
- `SUPPORT_GROUP_LINK`: Link to your support group
- `LOGS_GROUP_LINK`: Link to your logs group
- `OWNER_ID`: Your Telegram ID

## Usage

1. Add the bot to your Telegram group.
2. Start the bot by sending `/start`.
3. The bot will automatically start monitoring and protecting your group from copyright infringement.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
