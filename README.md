# Steamgifts-RPA-bot

A UIPath bot that will enter www.steamgifts.com giveaways automatically based on some configurable criteria present in config.xlsx.

Config values:
- **Entries**: The maximum number of entered users for a giveaway to be considered;
- **Description**: If this is equal to 1, then the bot will ignore giveaways that have a description;
- **RetryLimit**: A value indicating how many times the bot should initially try to load the website.

The bot will only enter giveaways listed publicly on the home page.
This bot is currently configured to work with Firefox and to close the browser before starting.
