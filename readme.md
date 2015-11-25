# SlackMe
SlackMe allows you to start a long running process and then forget it until it messages you at the Slack webhook you provide.

## Installation
Note: Because I'm lazy you're gonna have to go and install requests yourself. Simple enough.

Put `slackme` in a bin folder that's in your path.

## Usage
Note: You must set the "SLACK_WEBHOOK" environment variable to the webhook you get from Slack from the channel you wish to ping on completion.

To use, simply pass the command you wish to run as an argument to `slackme`.
e.g. The following command will wait for 5 seconds and then ping your webhook: `slackme sleep 5`