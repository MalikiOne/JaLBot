# JaLBot

Framework Built Off: <a href="https://github.com/SteamingMutt/DougleyBot">DougleyBot</a>

A chat bot for discord app based off <a href="https://github.com/chalda/DiscordBot/">Chalda's DiscordBot</a>, which is based off <a href="https://github.com/hydrabolt/discord.js/">discord.js</a>.

# Features:
Commands
JaLBOT (BETA) Discord Bot Commands:
The Bot only works in #general 
Available Commands:

Interative Commands (@x shoots @y)
- !pet. !dank, !shoot, !chill

Commands
!gif <image tags>
    returns a random gif matching the tags passed

!game <name of game>
    pings channel asking if anyone wants to play

!reddit [subreddit]
    Returns the top post on reddit. Can optionally pass a subreddit to get the top post there instead

!youtube <video name>
    gets youtube video matching tags

!steam
    Steam Community Group

!lasttweet
    Last Tweet From Timmac Twitter

!bd
    information about BetterDiscord

!johncena
    The one and only

!hype
    timmacHYPE Animated

!twitch <streamer name>
    timmac, shroomz, floppy, honyolo, monty. jounie, ming, mrmoon

!ping
    responds pong, useful for checking if bot is alive
	
## RSS:
    you can create an rss.json file adding rss feeds as commands. See rss.json.example in the config folder for details

## Other Bits and bobs
	If you want !game and !twitch commands 
	
# Instructions for using the files

Requires Node (probably 0.12)

Pull this repo

Edit/Create auth.json: 
Discord Bot's email/password
youtube API key (create one here https://console.developers.google.com)

<strong>Once installed and ready to be deployed, run the following in a command prompt in the folder you've copied JaLBot's files into.</strong>


"npm install"

"node discord_bot.js"
