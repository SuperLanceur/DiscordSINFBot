# DiscordSINFBot

# How to install ?
Clone the project and install the dependencies in the `src` folder.
``` npm install```

Create the `src/.env` folder, put it the content of `.env.example` by modifying the variables appropriately.

To "upload" the commands to the Discord helper, run
```node deploy-commands.js```

To run the bot, execute
```node bot.js```



## Roadmap dev
- [ ] An anonymous confession system. Members send a DM to the bot (!confess <message>), the admin approve it in a private channel (with a react) and the message will be then in the public channel) 
- [x] A bulk clear (!clear <number_message>)
- [ ] A meme contest event creator (!createcontest <channel_id> <emote> <start_date> <end_date>) with the score command
- [ ] A pin system for members with the role of pin management. (!pin by replying to the message to pin) 
- [ ] A welcoming DM to newcomers
- [ ] A poll system
- [ ] Some funny commands (!poop, !méchant, !criminel,...)
- [ ] A dynamic !help listing
