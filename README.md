[![Legion-Killfeed-Rated-Best.png](https://i.postimg.cc/5NGsshBK/Legion-Killfeed-Rated-Best.png)](https://postimg.cc/hfL8j33V) [![globe.gif](https://i.postimg.cc/2yjwBVjK/globe.gif)](https://postimg.cc/ph78wVFf)

# [Legion Killfeed's Slash Commands](https://killfeed.co/commands)

### Owner
| Command | Description |
|---------|-------------|
| `/reset stats player` | Wipe a player stats. [WARNING: This can't be undone!!!]|
| `/reset stats server` | Wipe a servers stats. [WARNING: This can't be undone!!!]|

### Setup
| Command | Description |
|---------|-------------|
| `/setup token` |  Add Server/s using a Nitrado Token (TOKEN USER ONLY)|
| `/setup channels` |  Automated set up (channel creation + channel perms) required to activate killfeed (TOKEN USER ONLY)|
| `/setup activate` |  Switch killfeed process back on if for any reason it's been switched off by the bot. (TOKEN USER ONLY)|
| `/set discord` |  Assign discord server (TOKEN USER ONLY)|

### Additional Settings
| Command | Description |
|---------|-------------|
| `/settings channels assign` |  Assign feed to channel (Admin+)|
| `/settings channels create` |  Add a channel from the list of channels for your selected server (Admin+)|
| `/settings flag_logs` |  Flag build logs to separate channel (Admin)|
| `/legion autostart` |  auto restart your server if stopped for 10mins|

### Admin
| Command | Description |
|---------|-------------|
| `/admin tracker` | Track command usage|

### Settings for Killfeed (Admin)
| Command | Description |
|---------|-------------|
| `/settings view` |  View your server's settings in Legion's database.|
| `/settings admin roles` |  Add killfeed permission to a discord role from a list of permissions (Admin)|
| `/settings linked role` |  Role that is assigned to members when they link their account|
| `/settings feeds clean` |  Enable/Disable purge messages for Status, Heatmaps, Leaderboards|
| `/settings economy` |  All economy settings except bounties|
| `/settings bounty` |  Assign your servers default bounty amount (required to enable bounty channel)|
| `/settings plon` |  Enable/Disable players use of `/plon` | command|
| `/settings set_plon_prefix` |  change the prefix to the players online voice channel count|
| `/logs autofeed` |  Assign Auto Download Logs Channel|

### Styling
| Command | Description |
|---------|-------------|
| `/legion colours view` | See what colours we have available for embeds|
| `/legion colours assign` | Assign embed colour to be displayed on embeds where-ever there is no pre-defined embed colour|
| `/settings add logo` | Add or remove a logo via URL for a selected server to be displayed on embeds where-ever there is a spare image slot available|
| `/settings locations` | Location settings for multiple feeds *a lot of options* (Admin)|

### Rename Options (Admin)
| Command | Description |
|---------|-------------|
| `/settings rename` | Change the server's name in the killfeed|
| `/server details edit` | Change server's name/description|
| `/server details view` | View server's name & description + other details|

### Scheduler (Only Damage Working)
| Command | Description |
|---------|-------------|
| `/schedule server restarts` | Schedule automated server restarts via bot. (WIP)|
| `/schedule damage cancel` | Cancel the automated base damage scheduler (Admin)|
| `/schedule damage enabled` | Set the day, time and timezone for base damage to be turned on (Admin)|
| `/schedule damage disabled` | Set the day, time and timezone for base damage to be turned off (Admin)|

### Full Map Auto Ban
| Command | Description |
|---------|-------------|
| `/settings mode autoban` | Autoban on Kill, Autoban on Death, No Autoban (Admin)|
| `/settings mode ignore` | Gamertags that are allowed to kill when autoban is on (Moderator)|

### Trader/Shoppi (Trader + Moderator + Admin + Founder + Owner) (BUGGED RIGHT NOW)
| Command | Description |
|---------|-------------|
| `/shoppi admin location` | Set trader location for items to spawn or disable to allow anywhere|
| `/shoppi admin status` | View Shoppi Status, pending orders, etc|
| `/shoppi config start` | Sends config files for trader that is coming soon|
| `/shoppi config setup` | Setup config (requires file) and assign channels for trader|
| `/shoppi config colour` | Set colour of embeds|
| `/shoppi config restarts` | Set time between restarts and whether bot restarts or not|

### Types.xml File Editing
| Command | Description |
|---------|-------------|
| `/types local validate` | Validate Local XML file (Local file, not on server)|
| `/types local boost` | Mass boost all nominals and mins to 'x' amount, eg, boost 100 to 1000 (Local file, not on server)|
| `/types local edit` | Bulk Edit Local Types.XML file by category, tag, usage, or value. (Local file, not on server)|
| `/types server boost` | Mass boost all nominals and mins to 'x' amount, eg, boost 100 to 1000 (Live server code)|
| `/updates` | Compare your files with the latest github version and get a list of missing items from your files (useful for updates)|

### Staff
| Command | Description |
|---------|-------------|
| `/admin getid` | Get the ID of a member (Usually used for devs)|
| `/admin search` | Search for a gamertag or member|
| `/admin plocs` | Current online player locations|
| `/admin force link` | Force link someone's discord to their gamertag|
| `/admin force unlink` | Force unlink a members discord from their gamertag|
| `/base damage` | Turn base & container damage on/off on your server|
| `/car_wipe` | This command does a car wipe, server restarts twice|
| `/last locations` | Last 20 locations for a gamertag|
| `/legion embed` | Send a message in an embed (must be less than 4000 characters)|
| `/logs download current` | Download Current Logfile|
| `/logs download kills` | Download Current Kills Only Logfile|
| `/logs download all` | Download All Logfiles|
| `/status` | Get the last restart and status of all servers|

### Economy
| Command | Description |
|---------|-------------|
| `/economy amoney user` | Allows an admin to give or remove money from a user's account.|
| `/economy amoney all` | Allows an admin to give or remove money from all linked accounts.|
| `/economy amoney reset` | Allows an admin to wipe money on.|
| `/economy amoney default` | Allows an admin to assign default balances.|

### File Editing
| Command | Description |
|---------|-------------|
| `/gameplay edit` | Edit your cfggameplay.json file for your selected server (Add or Remove) spawn gear/object spawner files in the cfggameplay.json file|
| `/admin spawner add` | Add items to spawn in via Events.xml & CfgEventSpawns.xml|
| `/admin spawner remove` | Remove items from spawn via Events.xml & CfgEventSpawns.xml|
| `/generate teleports` | Place 2 separate items where you want the teleport location to be and the safe location to be|
| `/generate qrcode` | Supply a URL, coords and select your compass orientation to get an in-game scannable QR Code Sign|

### Nitrado's Webinterface
| Command | Description |
|---------|-------------|
| `/webinterface update` | Update options on Nitrado's web interface|
| `/webinterface tasks list` | View your servers Nitrado-handled automated tasks|
| `/webinterface tasks add` | Add Nitrado-handled automated tasks|
| `/webinterface tasks delete` | Delete Nitrado-handled automated tasks from your server|
| `/webinterface upload` | Upload file to folder on your server|
| `/webinterface download` | Download file from any folder on your server|
| `/legion restart` | Restart your server|
| `/legion stop` | Stop your server|
| `/legion remove` | Remove stop/restart file|
| `/legion restartloop` | Break a restart loop for your server|

### Base Radar
| Command | Description |
|---------|-------------|
| `/base radar add` | Create a base radar for your selected server|
| `/base radar edit` | Edit a base radar for your selected server|
| `/base radar delete` | Delete a base radar from your selected server|
| `/base radar list` | List base radars for your selected server|

### Trader/Shoppi
| Command | Description |
|---------|-------------|
| `/shoppi mode` | Enable/Disable the use of Shoppi Auto Trader|
| `/shoppi items` | Sends item details, attachments, ammo, mags|
| `/shoppi pricing` | Sends pricing to trader channel|

### Heatmaps
| Command | Description |
|---------|-------------|
| `/heatmap Kills` |  PVP kills heatmap|
| `/heatmap Damage` |  PVP damage heatmap|
| `/heatmap Locations` |  Heatmap of player locations|
| `/heatmap Pinmap` |  Pinpoint map of player locations|
| `/heatmap Nitrado Usage` |  CPU/Ram usage|

### Gatekeeper (+ Owner + Founder)
| Command | Description |
|---------|-------------|
| `/add info_whitelist` | No description provided.|
| `/add upload_whitelist` | Upload a file to add gamertags to the whitelist|
| `/remove rebuild_whitelist` | Rebuild Whitelist|

### Banning
| Command | Description |
|---------|-------------|
| `/add ban` | Ban gamertag/gamertags|
| `/remove ban` | Unban gamertag/gamertags|
| `/view bans` | View banlist|

### Whitelisting
| Command | Description |
|---------|-------------|
| `/add whitelist` | Whitelist gamertag/gamertags|
| `/remove whitelist` | Unwhitelist gamertag/gamertags|
| `/view whitelist` | View Whitelist|

### Priority
| Command | Description |
|---------|-------------|
| `/add priority` | Prioritize gamertag/gamertags|
| `/remove priority` | Unpriority gamertag/gamertags|
| `/view priority` | View priority list|

### General (No Perms Needed)
| Command | Description |
|---------|-------------|
| `/subscribe` | Legion Killfeed Premium Subscription Price|
| `/help` | Select a category to view help commands|
| `/info` | Bot information|
| `/killfeed advert` | Legion Killfeed Advertisement|
| `/killfeed support` | Get a discord invite to Legion Killfeed's Support discord|
| `/bug` | Submit a bug report to the developers|
| `/fight` | Challenge a user to a fight, the loser will be timed out.|
| `/godmode` | A fake 'God Mode' command for the lols|
| `/plon` | Players online (Reply is slow for accuracy)|
| `/locate` | DM linked player their last logged location|
| `/last restart` | Get the last restart, next restart and current players online|

### Stats
| Command | Description |
|---------|-------------|
| `/global` | Global leaderboards|
| `/leaderboard` | Server's Leaderboard|
| `/link` | Link your discord to your gamertag|
| `/unlink` | Unlink your discord from your gamertag|
| `/stats` | Get stats for your selected server|
| `/mine` | Get stats for your selected server|

### Submissions
| Command | Description |
|---------|-------------|
| `/legion submit suggestion` | Send a killfeed suggestion/feature request to Legion's discord|
| `/legion submit roast` | Submit `Death Roasts` | for victim insults to Legion's discord|

### Shoppi/Trader (Player Commands) BUGGED RIGHT NOW
| Command | Description |
|---------|-------------|
| `/shoppi cart add` | Add items to cart before checkout|
| `/shoppi cart clear` | Remove items/items from cart before checkout|
| `/shoppi cart view` | View items in cart before checkout|
| `/shoppi cart checkout` | Checkout with cart (Pay & Upload json)|
| `/shoppi delivery` | Set coords for items to spawn|

### Base Ignore (Base Owner & Moderators+)
| Command | Description |
|---------|-------------|
| `/base ignore add` | Add a gamertag to the base radar ignore list|
| `/base ignore remove` | Remove a gamertag from the base radar ignore list|
| `/base ignore info` | List base radar info your current channel's base radar.|

### Money (Must be in economy channel)
| Command | Description |
|---------|-------------|
| `/economy help` | View the list of command and a brief description.|
| `/economy leaderboard` | Economy leaderboard (Linked members only)|

### Banking (Linked Members)
| Command | Description |
|---------|-------------|
| `/pay` | Pay someone (Must have played the server)|
| `/withdraw` | Withdraw money from your related server's bank|
| `/deposit` | Deposit money to your bank|
| `/bal` | Check your balance|

### Earning (Linked Members)
| Command | Description |
|---------|-------------|
| `/daily` | Claim your daily reward|
| `/fish` | Go fishing to earn money|
| `/work` | Work to earn money|
| `/rob` | Rob up to 50 percentage of cash from another user|

### Gambling (Linked Members)
| Command | Description |
|---------|-------------|
| `/slots` | Play slots|
| `/roulette` | Play a roulette game|
| `/rps` | Play a game of rock-paper-scissors|
| `/blackjack` | Play a game of blackjack|
| `/diceroll` | Play a dice roll game|

### Bounties (Must be in economy channel)
| Command | Description |
|---------|-------------|
| `/bounty add` | Add a bounty to someone|
| `/bounty view` | View servers bounty list|
| `/bounty pay` | Pay a bounty, either your own or someone else's|

[![LegionKillfeed](https://killfeed.co/a/i/lkb.png)](https://killfeed.co) ![Legion Killfeed Logo](https://killfeed.co/a/i/LK.gif)

## [Killfeed Website](https://killfeed.co/)
## [Commands](https://killfeed.co/commands)
## [FAQs](https://killfeed.co/faqs)
## [Legal](https://killfeed.co/legal)
## [Economy & Trader Tool](https://killfeed.co/tools)
## [Video Tutorials](https://killfeed.co/videos)

# FAQ Frequently Asked Questions - Legion Killfeed

## What is a killfeed in DayZ?
A killfeed is a feature that tracks and displays player kills, deaths, and other significant in-game events in real-time. Killfeeds are commonly used on DayZ servers to provide players with information about combat-related activities. 

## Why should I use a killfeed for my DayZ server?
Using a killfeed like [Legion Killfeed](https://killfeed.co) enhances the player experience by providing transparency and improving server management. It helps administrators monitor in-game activities and allows players to keep track of their performance.

## How does Legion Killfeed differ from other killfeeds?
Legion Killfeed, available at [Killfeed.co](https://killfeed.co), is the most advanced and reliable killfeed for DayZ servers. It offers real-time updates, customizable features, and seamless integration with Discord, making it the top choice for both PS4/PS5 and Xbox DayZ communities.

## Can I customize the events tracked by Legion Killfeed?
Yes, [Legion Killfeed](https://killfeed.co) is highly customizable. You can configure which events are tracked, such as kills, deaths, and loot pickups. Additionally, you can tailor the killfeed embeds with your server logo and your embed colour.

## How do I set up Legion Killfeed on my DayZ server?
Setting up [Legion Killfeed](https://killfeed.co) is straightforward. After subscribing to the service, a discord bot will automatically add a role to you which will be detected by Legion which will activate the commands for your account and you'll receive a DM with a detailed setup guide. The setup process is straight forward, two commands and the bot does most of the work.

## Does Legion delete anything?
Absolutely not! [Legion Killfeed](https://killfeed.co) is designed only to create channels, the only messages it ever deletes are it's own and that's just to reduce spam. Legion is unable to access messages as it doesn't have [message intents](https://support-dev.discord.com/hc/en-us/articles/4404772028055-Message-Content-Privileged-Intent-FAQ) enabled, without those intents our bot only see's members which is required for linking, assigning admin, adding roles, etc.

## Can I use Legion Killfeed with other DayZ bots and tools?
Yes, [Legion Killfeed](https://killfeed.co) cannot affect another bot in any way.

## Does Legion Killfeed affect server performance?
No, [Legion Killfeed](https://killfeed.co) spends less than 5 seconds connected to your server when downloading logs, everything is handled by the bot ones the logs are retrieved, except Nitrado server management commands (they ofc have to connect to the server).

## How often does Legion Killfeed update its features?
[Legion Killfeed](https://killfeed.co) is continuously updated with new features and improvements. The development team regularly releases updates based on community feedback to ensure that the killfeed remains the best option for DayZ servers, Soul works day and night updating the code & website.

## How do I contact support for Legion Killfeed?
If you need assistance with [Legion Killfeed](https://killfeed.co), you can reach out to the support team via the [Discord server](https://discord.gg/LegionKillfeed). The support team is responsive and ready to help with any questions or issues you may have.

## Can I try Legion Killfeed before subscribing?
Currently, [Legion Killfeed](https://killfeed.co) offers subscription-based services. However, the affordable pricing and top-rated features make it a worthwhile investment for any DayZ server owner looking to enhance their server with a professional killfeed, it's $7USD minimum.

## What are the benefits of using Legion Killfeed over free alternatives?
While free killfeeds may offer basic functionality, [Legion Killfeed](https://killfeed.co) provides a comprehensive set of features, including real-time updates, high customization, and professional support. Its reliability and seamless Discord integration make it the preferred choice for serious DayZ server administrators, plus free alternatives have a higher risk of selling your data to third parties and the other concerns surrounding them.

## How does Legion Killfeed handle data privacy?
[Legion Killfeed](https://killfeed.co) prioritizes data privacy and security. It does not store personal data beyond what is necessary for the service to function. Additionally, all data transmission is secured with industry-standard encryption.

## Can I use Legion Killfeed on multiple servers with a single subscription?
Yes, [Legion Killfeed](https://killfeed.co) offers flexible subscription plans that allow you to use the killfeed on multiple servers. Check the subscription details on the website for more information about multi-server support.

## How does Legion Killfeed integrate with Discord?
[Legion Killfeed](https://killfeed.co) integrates with Discord by sending semi-real-time notifications directly to your server's designated channels. This allows players and admins to stay informed about in-game events, even when they’re not logged into the game.

## Is there a community around Legion Killfeed?
Yes, [Legion Killfeed](https://killfeed.co) has an active community of DayZ server owners and players. You can join the community through the [Discord server](https://discord.gg/LegionKillfeed), where you can share tips, request features, and get help from other users.

## How do I get started with Legion Killfeed?
To get started with [Legion Killfeed](https://killfeed.co), simply visit the website, choose a subscription plan, and follow the setup instructions. You'll be up and running with the best DayZ killfeed in no time!

## [Killfeed Website](https://killfeed.co/)
## [Commands](https://killfeed.co/commands)
## [FAQs](https://killfeed.co/faqs)
## [Legal](https://killfeed.co/legal)
## [Economy & Trader Tool](https://killfeed.co/tools)
## [Video Tutorials](https://killfeed.co/videos)
