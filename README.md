How to customize/setup the basic bot.

Setup the bot:
1) open the file in "data/settings.json"
2) Create a bot token by going to https://discordapp.com/developers/applications/me click "New App" enter the bot name, image and description. Click "Create App" then scroll down to the "Bot" section. Click "Create a bot user" this will make a new bot user. Make sure to enter a bot name.You will then click done (Or something like that). 
3) Change "BOTTOKEN" to your discord bot token, you get this by going to the link above after making the bot. Then "click to reveal" next to Token under the "Bot" section. Then copy the token and change "BOTTOKEN" to that token that is given to you.
4) Change "CLIENTID" to your client id what is found on the link above at the top. Copy the ID then change "CLIENTID" to that.
5) Change "!BOTTAG" to the tag you want to use. For example for CMB we use "!" as our tag, but you can use anything.
6) Chang "YourOwnerID" to your bots owner ID. This is found at the link where you made the bot. Then next to "Username" under the "bot" section is your "OWNERID"
7) Save the file

Starting the bot:
1) Own a server (Can be VPS)
2) Install NODE JS - https://nodejs.org/
3) Upload the files to a folder on the server
4) Navigate to the folder in SSH/Command Line
5) Type "node bot.js"
6) This should start the bot.
