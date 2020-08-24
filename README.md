# DiscordNuke

# Setup and Usage
To set up the bot, you'll need the bot token and a prefix. 

If you don't know how to get a token, you can watch this: https://www.youtube.com/watch?v=RsJgi1gPdjA .
Once you obtain your bot token, paste it in the script as shown below. Make sure the token is IN THE QUOTATION MARKS.

Ex:
```token = "NzQzOTU1Mzk3NjcyNDM1NzYy.XzcMdA.cSXie4geIGekaQkk6dXPnTjoJqc"```

After getting your bot token, set your prefix by typing your prefix as shown below. Again, make sure it's in the quotes or it won't work.

Ex:
```prefix = !```

# Nuke Config
One last thing, you can configure is the webhook names, what they spam, what the channel names should be, and whether the bot should nuke as soon as it joins.
In order to make it nuke on join, change 
```nuke_on_join = False``` to ```nuke_on_join = True```
When changing the names and other stuff, don't forget to add a comma after each phrase.

# Commands
help : DMs you all of the bot's commands.

nuke : Nukes the server.

spam : Spams all channels.

ccreate <amount> <name> : Creates channels.

cdelete : Deletes all channels.

logout : Exits the script.
