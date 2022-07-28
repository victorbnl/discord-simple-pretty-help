# Discord simple pretty help

A simple yet pretty help menu for discord.py bots

<p align="center">
    <table>
        <tr>
            <td><img src="https://raw.githubusercontent.com/victorbnl/discord-simple-pretty-help/main/.readme/bot_help.png"></td>
            <td><img src="https://raw.githubusercontent.com/victorbnl/discord-simple-pretty-help/main/.readme/command_help.png"></td>
        </tr>
    </table>
</p>

## Installation

```
pip install git+https://github.com/victorbnl/discord-simple-pretty-help
```

## Usage

```py
from discord_simple_pretty_help import SimplePrettyHelp
bot = commands.Bot(help_menu=SimplePrettyHelp())
```

## Parameters

- `color`: color of the embed (default: 0x5865F2)
