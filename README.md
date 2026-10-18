# Mini AI App Launcher

A lightweight Windows desktop app that launches installed apps and games from English text commands.

## Features

- Search Start Menu and Desktop shortcuts
- Find installed apps registered in Windows
- Launch installed Steam and Epic Games titles
- Show a chooser when a command matches multiple apps or games
- Launch AyuGram from its shortcut or installation entry; if it is not found, open Telegram Web in a random detected Chrome or Edge profile
- Browse the apps and games found on the current PC
- English interface and English command phrases
- Uses only Python\'s standard library

## Requirements

- Windows 10 or Windows 11
- Python 3.9 or newer with Tkinter (included with the standard Windows Python installer)

## Run

Open PowerShell in this folder and run:

```powershell
python mini_ai_launcher.py
```

## Commands

Examples:

- `open Telegram`
- `launch Discord`
- `play Minecraft`
- `please start Spotify`
- `open AyuGram`

Use **All apps** to see what the launcher found. If several items match, select the desired entry in the chooser window.

## Notes

The launcher searches the computer on which it runs. An app or game must already be installed there. Steam and Epic games are started through their respective launchers. Browser profile selection is used only for the Telegram Web fallback when AyuGram is not found. Installed application names may appear in the language used by Windows or the app publisher.
