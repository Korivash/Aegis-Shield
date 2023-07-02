## UwU Tracker Discord Bot
UwU Tracker is a Discord bot designed to help server owners track and manage undesirable users within their guilds. The bot logs user information in a database and provides commands to ban, unban, and manage notification channels. Additionally, it sends notifications to all guilds when a user is banned or when a banned user enters a guild.

## Commands
ban: Bans a user and adds them to the banned list.

Usage: !ban <user>
Example: !ban @creepy_user#1234
banned: Lists all users currently banned in all guilds.

Usage: !banned
Example: !banned
remban: Removes a user's name from the banned list (does not unban them).

Usage: !remban <user>
Example: !remban @creepy_user#1234
set-channel: Sets the channel where the bot sends notifications.

Usage: !set-channel <channel>
Example: !set-channel #notifications
unset-channel: Removes the current notification channel.

Usage: !unset-channel
Example: !unset-channel
Events
UwU Tracker bot notifies all guilds when a user is banned or when a banned user enters their guild. The notifications are sent to the configured notification channel.

## Configuration
Just invite UwU Tracker to your server via this URL: 
Make sure to give it admin permissions just like any other discord bot.


## Usage
Invite the UwU Tracker bot to your Discord server using the provided invite link.
Set up the necessary permissions for the bot to ban users and manage channels.
Configure the bot by setting the notification channel using the !set-channel command.
Use the available commands (!ban, !banned, !remban, !set-channel, !unset-channel) to manage the banned users and notification channel.
License
The UwU Tracker Discord bot is open-source software released under the MIT License. 
