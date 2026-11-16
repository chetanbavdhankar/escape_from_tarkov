# Tarkov Quest Tracker

[Open the live Tarkov Quest Tracker](https://chetanbavdhankar.github.io/escape_from_tarkov/) or open `index.html` locally.

## Data sources

We embedded 540 task records from the [August 2026 community archive](https://github.com/szepiz/tarkov-quest-data), which combines Tarkov.dev, wiki data, and in-game observations. Tour unlocks follow the [Tarkov Wiki](https://escapefromtarkov.fandom.com/wiki/Tour). Trader descriptions are matched by quest ID from an [archived English localization](https://github.com/sp-tarkov/server-csharp/blob/main/Libraries/SPTarkov.Server.Assets/SPT_Data/database/locales/global/en.json).

## How it works

A single HTML file uses CSS and JavaScript to build collapsible branches from recorded prerequisites in each game mode. Click a card to expand it or use its link to open task or story details. The browser saves your progress locally.
