# Anonymous Bot for Slack

## What it does


When someone posts `/anon @user Some anonymous text`, that message is sent to this simple service, which sends the text back to the specified user with a modified text, omitting the information about the author of the message.

To avoid revealing your identity by accidentally typing the wrong command, it's recommended to post all messages in your private conversation with SlackBot.

## Usage

*Assuming that the configured slash-command is called "/anon" *

- `/anon help` -- Displays the help information
- `/anon <message>` -- Sends a message
