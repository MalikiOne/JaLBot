# JaLBot

Framework Built Off: 

- <a href="https://github.com/SteamingMutt/DougleyBot">DougleyBot</a>
	A chat bot for discord app based off <a href="https://github.com/chalda/DiscordBot/">Chalda's DiscordBot</a>, which is based off <a href="https://github.com/hydrabolt/discord.js/">discord.js</a>.

- <a href="https://github.com/TehSeph/Neko.js/">Neko.js</a>
	A chat bot for discord app based off <a href="https://github.com/Kusoneko/Nekobot/">Port of Nekobot (by Kusoneko)</a>, which is based off <a href="https://github.com/hydrabolt/discord.js/">discord.js</a>. (Borrowed the !pet command)

# Features:
Commands

JaLBOT (BETA) Discord Bot Commands:

Available Commands:

Interative Commands

- !pet. !dank, !shoot, !chill <user>

Commands

- !gif <image tags>

	returns a random gif matching the tags passed. !gif cute cats doing stuff

- !game <name of game>
    
	Pings channel asking if anyone wants to play

- !reddit [subreddit]
    
	Returns the top post on reddit. Can optionally pass a subreddit to get the top post there instead

- !youtube <video name>
    
	Gets youtube video matching tags

- !steam
    
	Steam Community Group

- !lasttweet
    
	Last Tweet From Timmac Twitter

- !bd
    
	Information about BetterDiscord

- !johncena
    
	The one and only
	
- !twitter <Twitter username>
    
	(http://twitter.com/<streamers name>)

- !twitch <streamer name>
    
	(http://twitch.tv/<streamers name>)

- !ping
    
	responds pong, useful for checking if bot is alive
	
## RSS:
    you can create an rss.json file adding rss feeds as commands. See rss.json.example in the config folder for details

## Other Bits and bobs
	If you want !game, !twitch & !twitter commands please be sure to edit the games and streams JSON files to fit your needs!
	
## Instructions for using the files
Requires Node (probably 0.12)
Pull this repo (Or Download Zip and Extract)

Edit/Create auth.json: 
Discord Bot's email/password
youtube API key (create one here https://console.developers.google.com)

<strong>Once installed and ready to be deployed, run the following in a command prompt in the folder you've copied JaLBot's files into.</strong>


"npm install"

"node discord_bot.js"
