### THIS REPOSITORY IS A FORK OF [NIKKI](https://github.com/CrosswaveOmega/NikkiBot)!

# Nikki Bot

Nikki Bot is a personal multipurpose, experimental Discord bot written using the discord.py library.

## Features

1. **TCGuildTask system**: This feature allows for the creation of specialized server unique tasks that execute at regular intervals, such as every day/week/month at specific times, on specific weekdays, and so on.
   Data for each task is represented by the entries within a SQLAlchemy table with the server ID, the name of the task, the interval, a channel ID for the 'autolog' channel, and the datetime for the next run.
   The tasks can be customized by adding coroutines to the Guild_Task_Functions class, within the bot's Cogs.

2. **Helldivers 2 Features!**: View the current status of the Galactic War in Helldivers 2 at a high, technical level.

## Current Requirements

Python 3.13 or higher!

- discord.py
- SQLAlchemy
- python-dateutil
- sqlitedict
- keyring
- lancedb
- [markitdown](https://github.com/microsoft/markitdown)
- [Helldivers2api.py](https://github.com/CrosswaveOmega/hd2api.py)

Please make sure to install the latest node.js runtime on your system to ensure that the Summarizer works.

## Technical Features

- Experimental autosync system which only syncs app command trees if it detects a difference between saved dictionary representations of the App Command Tree.
