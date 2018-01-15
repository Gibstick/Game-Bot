# Game-Bot

This Discord bot takes in a Steam game's name and returns its link on the Steam Store based on Valve's search suggest feature.

## Dependencies

`Discord.py`, `lxml`:
```
python3 -m pip install -U discord.py lxml
```

Set the environment variable `GAME_BOT_TOKEN` as your token, eg.

```
 export GAME_BOT_TOKEN=foobar
python3 game_bot.py
```

If you have `HISTCONTROL` set to `ignoreboth` or `ignorespace` in bash,
prepend a space before any command containing your token to prevent it from
showing up in your history.

**Make sure you are running Python 3.4.2+!**

## To do:

Add server counter for DiscordBots.org

<del>Remove "Looking for x" string output, and set up "Game not found" instead.</del>
