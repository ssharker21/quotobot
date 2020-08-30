# Quotobot
A Discord bot that tells quotes!

[![Node.js CI](https://github.com/ssharker21/quotobot/workflows/Node.js%20CI/badge.svg)](https://github.com/ssharker21/quotobot/actions)  [![GitHub license](https://img.shields.io/github/license/ssharker21/quotobot)](https://github.com/ssharker21/quotobot/blob/master/LICENSE)  [![Click to invite to your server](https://img.shields.io/static/v1?label=Invite%20to&message=your%20server&color=7289DA&logo=Discord)](http://quotobot.ml)


# [INVITE THE BOT TO YOUR SERVER!](http://quotobot.ml)

### Special thank you to [Uddesh](https://github.com/UddeshJain)
We used part of his [weather bot code](https://github.com/UddeshJain/Discord-Weather-Bot) and slightly modified it for our project.

## Or do you want to host and tweak the bot yourself?

### How to set up the config.json
- Make a copy of config-example.json and call it config.json. 

- Delete the entire line with `"instructions"` if you want to.

- Change the prefix if you like (keep it inside the quotes). 

- **Where it says `"your-token-here"`, paste in your Discord bot token (also inside the quotes).** If you want to make the bot use an environment variable, set QBTOKEN to your token and leave the config.json entry at `"your-token-here"`.

- If you want the bot to output its invite link on startup, change
```json
"clientID-example": "123456789012347",
```
to
```json
"clientID": "123456789012347",
```

making sure to change the number to your client ID inside the quotes.

You can also change the status that the bot shows (it'll be prefixed with *Watching*, though) by changing the `help-domain-example` to `help-domain` and adding your text in the value for that. Example complete config file:
```json
{
    "prefix": "&&",
    "token": "abcdrkhjregjl.efghfioeigtj",
    "help-domain": "my-bot-site.qb",
    "clientID": "12343546798",
    "permissionValue": 0
}
```
### Run the bot
Make sure you have NodeJS installed and open a command prompt/terminal in the folder where these files are. Then run:
```bash
npm install
node index.js
```
### Tentative Timeline
Publish v1.0 of the bot: **August 30** (by the latest): **70+ QUOTES! The quotes will be nice and embedded!**

Publish v.1.0.x of the bot: **We might periodically add more quotes and features, including general features unrelated to quotes! There is no deadline as school will restart and time to work on this project will be limited.**

Any pull requests are appreciated.
