# Annoying Grammar Checker Bot

A Discord bot that checks chat messages for spelling & grammar mistakes (using [Harper](https://github.com/FranBowden/harper)) and replies with corrections, plus an angry GIF using Giphy.

Built with Node.js, discord.js, and Harper. This bot is designed to run in Discord servers

Add to server: https://sh-url.com/TUHiG7

## Commands

- `/ping` — health check, replies with "Pong!"
- `/language` — set grammar dialect (American/British English) for the server
- `/gif-feature-toggle` — enable or disable the angry GIF reply for the server
- `/grammar-check-toggle` — enable or disable grammar checking entirely for the server
- `/strictness` — set how strict grammar checking is for the server:
  - `relaxed`
  - `standard` (default)
  - `strict`
