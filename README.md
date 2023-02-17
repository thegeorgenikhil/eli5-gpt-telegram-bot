[![GitHub go.mod Go version of a Go module](https://img.shields.io/github/go-mod/go-version/torquemada163/telegram-chatgpt-golang-bot.svg)](https://github.com/torquemada163/telegram-chatgpt-golang-bot)
[![GitHub license](https://img.shields.io/github/license/torquemada163/telegram-chatgpt-golang-bot.svg)](https://github.com/torquemada163/telegram-chatgpt-golang-bot/blob/main/LICENSE)
[![Github all releases](https://img.shields.io/github/downloads/torquemada163/telegram-chatgpt-golang-bot/total.svg)](https://GitHub.com/torquemada163/telegram-chatgpt-golang-bot/releases/)
[![GitHub release](https://img.shields.io/github/release/torquemada163/telegram-chatgpt-golang-bot.svg)](https://GitHub.com/torquemada163/telegram-chatgpt-golang-bot/releases/)
[![GitHub forks](https://badgen.net/github/forks/torquemada163/telegram-chatgpt-golang-bot/)](https://GitHub.com/torquemada163/telegram-chatgpt-golang-bot/network/)
[![GitHub issues](https://img.shields.io/github/issues/torquemada163/telegram-chatgpt-golang-bot)](https://GitHub.com/torquemada163/telegram-chatgpt-golang-bot/issues/)

# ELI5 Telegram Bot using OpenAI API

## Install

Just a few simple steps:

1. Clone repository
2. Rename file `config.yaml.example` to `config.yaml` and set up your tokens (OpenAI and Telegram) in file
3. Run `go mod tidy`
4. Run `go run main.go`

## Usage

This is a simple Telegram bot that uses the OpenAI API to generate a ELI5 explanation of a given topic or phrase.

### Commands

- `/start` - Start the bot
- `/topic <topic>` - Generate a ELI5 explanation of a given topic
- `/phrase <phrase>` - Generate a ELI5 explanation of a given phrase
