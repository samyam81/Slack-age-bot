# Slack-age-bot

This repository contains a Slack bot written in Go that calculates age based on the year of birth provided in a Slack command.

## Module

This project uses the module:
```
github.com/samyam81/Slack-age-bot
```

## Requirements

- *Go version 1.16 or higher*

## Dependencies

The following dependencies are managed using `go.mod`.

## Usage

To run the bot, set the following environment variables:

- `SLACK_BOT_TOKEN`: Your Slack bot token
- `SLACK_APP_TOKEN`: Your Slack app token

Then, execute the main program:

```bash
go run main.go
```

## Functionality

The bot listens for commands on Slack. It includes a command handler for calculating age based on the provided year of birth (`my yob is <year>`).

### Example Command

```
my yob is 1990
```

This will calculate the age based on the current year (2021 in this case) and reply with the calculated age.

