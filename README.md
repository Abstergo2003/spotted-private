# spotted-pivate
This bot is private, and you have to host it yourself
You should consider this bot as a fun tool rather than actual bot
I can guarantee full anonymous of messages sent on spotted using this bot, but i cant guarantee that your server will not be spammed,
due to me unable to provide logs or use permissions via this bot

Configuration:
Open data/commands.json there are fields like 'your channel/server id' fill them with channel or server id based on whats provided.
if you open this file with windows note fields will be somewhere in 4th line
Open data/settings.json and type your bot token and client id, (https://discord.com/developers/applications - use this to create your application in discord database, dont worry its their official link)

Running bot
1 method on your computer
- install node.js and open it
- type node 'bot directory'/bot.js
- done
- add bot to your server

2 method on heroku (free)
- create Procfile and put it in bot's directory
- in procfile type 'worker: node bot.js'
- deploy bot to heroku
- change dyno formation to worker 
- add bot to your server
- done

To add bot to your server insert this url in your web browser: https://discordapp.com/oauth2/authorize?client_id='your aplication id'&scope=bot&permissions=2146958591

Youre welcome to insert your own changes to this bot but it was created using Discord Bot Maker so it might be really hard to do without this tool, 
Any true programmer should rather try writting his own bot from scratch.
