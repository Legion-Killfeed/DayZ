**Legion Killfeed – Full Commands**

# LEGION KILLFEED TRUST, FAQ & REVIEWS

> ## Special Announcement
>
> I categorically deny the allegation that Legion Killfeed collects, sells, abuses, leaks, or misuses customer files or server data.
>
> That claim is false, malicious, and commercially damaging. It is not a review. It is not an opinion. It is a factual accusation of misconduct, and it has been pushed by competitors and competitor-linked accounts to damage trust in Legion Killfeed.
>
> Legion Killfeed uses access only for the features customers authorise, including Nitrado integration, log processing, server tools, killfeeds, stats, and related bot functions.
>
> XML files are not precious gemstones; they are easy to make. I do not know who would pay for them, but I certainly have never sold files. I give my own files out regularly.
>
> But unlike the false accusers, we have proof available, including technical context, records, timelines, screenshots, and evidence showing the source and pattern of these allegations.
>
> Anyone repeating the false allegations and anyone relying on anonymous Reddit comments, competitor pages, or forum pile-ons should ask for evidence instead of treating obvious smear content as fact.
>
> - **Evidence:** https://they-wish-i.died.space
> - **Google post:** https://share.google/ozE8X655mIr6w4v5R
>
> ## FAQ
>
> ### Does Legion Killfeed sell, leak, abuse, or misuse customer files or server data?
> No. Legion Killfeed categorically denies that allegation. Access is used only for customer-authorised features such as Nitrado integration, log processing, server tools, killfeeds, stats, and related Discord bot functions.
>
> ### What does Legion Killfeed use Nitrado access for?
> Nitrado access is used for authorised DayZ console server features including setup, log processing, killfeeds, stats, server tools, scheduled actions, file utilities, and related bot functions.
>
> ### Why does Legion Killfeed process logs?
> Logs power the DayZ killfeed, PVP/PVE stats, player activity, connect/disconnect feeds, heatmaps, base radar, moderation context, and server admin workflows.
>
> ### Where can I read Legion Killfeed reviews?
> Reviews and customer feedback are linked from https://killfeed.co/reviews and Trustpilot. Review themes commonly include fast support, useful automation, clean embeds, reliable DayZ console tools, and practical setup help.
>
> ### Does Legion Killfeed advertise or chase customers?
> No. Legion Killfeed does not advertise or seek people out. People find Legion themselves through the website, wiki, Discord, tools, reviews, and community recommendations.

<!-- BOT-COMMAND-INVENTORY:START -->
# BOT SOURCE COMMAND INVENTORY

> Source checked against the current `bot/**/*.py` slash-command decorators. This inventory excludes developer/support-only debug commands and lists the live public command paths registered by the bot.

## Setup
> - `/setup activate` - Switch log download on
> - `/setup assign discord` - Token user with admin perms can assign discord
> - `/setup channels` - Setup all channels for a selected server
> - `/setup token` - Add Server by Nitrado Token

## Settings
> - `/settings autoban cheats` - Configure cheat autobans.
> - `/settings autoban config` - Autoban options, on kill, death or off.
> - `/settings autoban whitelist` - Whitelist to be safe from whole map's ban functions
> - `/settings channel assign` - Assign feed to channel
> - `/settings channel create` - Add a channel from the list of channels for your selected server
> - `/settings configure color` - Assign embed color for your server
> - `/settings configure glitchfeed` - Toggle which items from build logs to send to the glitch feed channel
> - `/settings configure linkrole` - Assign the role to be added to linked users.
> - `/settings configure locations` - Set locations settings for separate feeds
> - `/settings configure logo` - Add or remove a logo via URL for a selected server
> - `/settings configure misc` - Configure miscellaneous settings
> - `/settings configure name` - Rename server in killfeed?
> - `/settings forget server` - Disconnect a server without deleting its saved stats or history.
> - `/settings playersonline` - Enable/Disable players online (settings & /plon command)
> - `/settings view` - View Legion's stored settings for your servers.

## Server
> - `/server break loop` - Break a restart loop for your server
> - `/server delete stop` - Remove stop file
> - `/server fetch` - Fetch faction details from member
> - `/server restart` - Restart your server
> - `/server stop` - stop your server

## Logs
> - `/logs auto download` - Assign Auto Download Logs Channel
> - `/logs download all` - Download All Logfiles
> - `/logs download current` - Download Current Logfile
> - `/logs download kills` - Download Current Kills Only Logfile

## Nitrado
> - `/nitrado dashboard damage` - Change base damage settings for Nitrado's webinterface
> - `/nitrado dashboard settings` - Update settings on Nitrado's web interface dashboard
> - `/nitrado details update` - Change Nitrado server name/description + add special boost character
> - `/nitrado details view` - View server name & description + other details
> - `/nitrado tasks add` - Add automated task via Nitrado
> - `/nitrado tasks delete` - Delete automated task via Nitrado
> - `/nitrado tasks list` - View servers automated tasks

## Files
> - `/file download` - Download file from any folder on your server
> - `/file gameplay damage` - Edit your cfggameplay.json file to enable/disable base damage for your selected server
> - `/file gameplay edit` - Add or Remove spawn gear and object files from the cfggameplay.json file
> - `/file upload` - Upload file to folder on your server

## Scheduler
> - `/scheduler damage configure` - Set the day, time and timezone for base damage to be turned on & off
> - `/scheduler gameplay edits` - Add cfggameplay.json automated file editting
> - `/scheduler gameplay remove` - Cancel cfggameplay.json automated file editting for matching file name
> - `/scheduler settings configure` - Configure settings for Legion Killfeed to automate.
> - `/scheduler settings damage` - Enable/Disable bot handled automated base damage scheduler
> - `/scheduler settings restarts` - Enable/Disable bot handled-restarts.
> - `/scheduler settings view` - View current base damage scheduling configuration

## Admin
> - `/admin force fight` - Force two users to a fight, the loser will be timed out, if they don't accept, both are timed out.
> - `/admin force link` - Force link someone's discord to their gamertag
> - `/admin force unlink` - Force unlink a members discord from their gamertag
> - `/admin getid` - Get the ID of a member (Usually used for devs)
> - `/admin player locations` - Current online player locations
> - `/admin player search` - Search for a gamertag or member
> - `/admin spawner add` - Add items to spawn in via Events.xml & CfgEventSpawns.xml
> - `/admin spawner nuke` - Provide coords to have a 'nuke' of explosions to spawn on server
> - `/admin spawner remove` - Remove an event from events.xml & CfgEventSpawns.xml
> - `/admin tracker` - Track command usage

## Banlist
> - `/ban add` - Ban gamertag/gamertags
> - `/ban remove` - Unban gamertag/gamertags
> - `/ban view` - View banlist

## Alt Detection
> - `/alt detector ban` - Ban all associated gamertags, alts and devices
> - `/alt detector search` - Search for associated gamertags, alts and devices
> - `/alt detector state` - Enable/Disable alt detection (requires disableMultiAccountMitigation to be disabled)
> - `/alt detector unban` - unban all associated gamertags, alts and devices
> - `/alt detector view` - View accounts with persistence set to actively monitor

## Priority
> - `/priority add` - Prioritize gamertag/gamertags
> - `/priority remove` - Registered bot command.
> - `/priority view` - View priority list

## Whitelist
> - `/whitelist add` - Add player/players to whitelist
> - `/whitelist remove` - Remove gamertag/gamertags from whitelist
> - `/whitelist view` - View Whitelist

## Embeds
> - `/embed build` - Send a message in an embed

## Generators
> - `/generate qrcode sign` - Supply a URL, coords and select your compass orientation to get an in-game scannable QR Code Sign
> - `/generate teleports file` - Place 2 separate items where you want the teleport location to be and the safe location to be

## Banking
> - `/banking adjust all` - Allows an admin to give or remove money from all linked accounts.
> - `/banking adjust user` - Allows an admin to give or remove money from a user's account.
> - `/banking help` - View the list of command and a brief description.
> - `/banking leaderboard` - Economy leaderboard (Linked members only)
> - `/banking manage reset` - Admin command to wipe money.
> - `/banking settings` - All economy/banking settings except bounties

## Bounties
> - `/bounty add` - Add a bounty to someone
> - `/bounty admin clean` - Admin commands for bounties.
> - `/bounty admin min` - Admin commands for assigning bounty minimum.
> - `/bounty admin pay` - Admin commands for paying bounties.
> - `/bounty pay` - Pay a bounty, either your own or someone else's
> - `/bounty view` - View servers bounty list

## Player / General
> - `/bal` - Check your balance
> - `/blackjack` - Play a game of blackjack
> - `/daily` - Claim your daily reward
> - `/deposit` - Deposit money to your bank
> - `/diceroll` - Play a dice roll game
> - `/fight` - Challenge a user to a fight, the loser will be timed out.
> - `/fish` - Go fishing to earn money
> - `/global` - Global leaderboards
> - `/godmode` - A fake 'God Mode' command for the lols
> - `/help` - Select a category to view help commands
> - `/info` - Bot information
> - `/leaderboard` - Server's Leaderboard
> - `/link` - Link your discord to your gamertag
> - `/locate` - DM linked player their last logged location
> - `/mine` - Get stats for your selected server
> - `/pay` - Pay someone (Must have played the server)
> - `/plon` - Players online (Reply is slow for accuracy)
> - `/rob` - Rob up to 50 percentage of cash from another user
> - `/roulette` - Play a roulette game
> - `/rps` - Play a game of rock-paper-scissors
> - `/slots` - Play slots
> - `/stats` - Get stats for your selected server
> - `/status` - Get the last restart and status of all servers
> - `/subscribe` - Legion Killfeed Premium Subscription Price
> - `/unlink` - Unlink your discord from your gamertag
> - `/withdraw` - Withdraw money from your related server's bank
> - `/work` - Work to earn money

## Shoppi
> - `/shoppi admin location` - Set trader location for items to spawn or disable to allow anywhere
> - `/shoppi admin status` - View Shoppi Status, pending orders, etc
> - `/shoppi cart add` - Add items to cart before checkout
> - `/shoppi cart checkout` - Checkout with cart (Pay & Upload json)
> - `/shoppi cart clear` - Remove items/items from cart before checkout
> - `/shoppi cart view` - View items in cart before checkout
> - `/shoppi config restarts` - Set time between restarts and whether bot restarts or not
> - `/shoppi config setup` - Setup config (requires file) and assign channels for trader
> - `/shoppi config start` - Sends config files for trader that is coming soon
> - `/shoppi delivery` - Set coords for items to spawn
> - `/shoppi items` - Sends item details, attachments, ammo, mags
> - `/shoppi mode` - Enable/Disable bot-managed restart handling for Shoppi
> - `/shoppi pricing` - Sends pricing to trader channel

## Tickets
> - `/ticket close` - Close a thread
> - `/ticket colours` - See what colours we have available for embeds
> - `/ticket refresh` - Re-post the embeds
> - `/ticket setup` - Setup ticket system

## Flag Map
> - `/flagmap setup channel` - Assign a channel
> - `/flagmap setup help` - Help Command for the Flag Map feature
> - `/flagmap setup locations` - assign up to 5 flag locations
> - `/flagmap setup mode` - Assign between Faction Domination and Team Conquest modes
> - `/flagmap setup teams` - Assign a flag and name for two team mode
> - `/flagmap view active` - View current setup for a flagmap

## Types XML
> - `/types local boost` - Mass boost all nominals and mins to 'x' amount, eg, boost 100 to 1000
> - `/types local edit` - Bulk Edit Local Types.XML file by category, tag, usage, or value.
> - `/types local validate` - Validate Local XML file
> - `/types server boost` - Mass boost all nominals and mins to 'x' amount, eg, boost 100 to 1000

## Compare XML
> - `/compare types` - Compare your types.xml with the latest version
> - `/compare updates` - Compare your files with the latest version and get a list of updates.

## Factions
> - `/faction acreate` - Create a faction
> - `/faction create` - Create a faction
> - `/faction ignorelist` - Add/Remove gamertag to your default ignore list
> - `/faction members` - Add/Remove/Demote faction members/admins
> - `/faction view` - View your faction embed

## Lottery
> - `/lottery buy` - Buy a lottery ticket!
> - `/lottery check` - Registered bot command.
> - `/lottery draw` - Draw the lottery winner
> - `/lottery tickets` - Show who has purchased what ticket numbers

## Heatmaps
> - `/heatmaps` - Heatmaps of player kills or player locations

## Killfeed
> - `/killfeed support` - Get a discord invite to Legion Killfeed's Support discord

## Last Seen
> - `/last locations` - Last 30 locations for a gamertag
> - `/last restart` - Get the last restart, next restart and current players online

## Submit
> - `/submit bot roast` - Submit Roasts To Legion Killfeed
> - `/submit bot suggestions` - Send a killfeed suggestion/feature request to Legion
> - `/submit bot todo` - Dev only command to post in to-do list

## Wipe
> - `/wipe cars` - This command does a car wipe, server restarts twice
> - `/wipe stats player` - Wipe a player stats. [WARNING: This can't be undone!!!]
> - `/wipe stats server` - Wipe a servers stats. [WARNING: This can't be undone!!!]

<!-- BOT-COMMAND-INVENTORY:END -->

# ADMIN & SETUP COMMANDS

> ## SETUP COMMANDS
>
> ### /setup token
> - **Role:** Subscriber Only
> - **Description:** Adds a token for a server (Nitrado API). Registers your Discord server with Nitrado for Legion automation.
> - **Options:**  
>   - `token` (required): Nitrado API token
> - **Expected Behaviour:** Registers the Nitrado server with Legion Killfeed.
> - **Example:** `/setup token token:XYZ123TOKEN`
>
> ### /setup channels
> - **Role:** Owner, Founder, Admin
> - **Description:** Auto-setup common channels & their perms for a server. Creates and configures all Discord channels needed for Legion automation.
> - **Options:** None
> - **Expected Behaviour:** Bot creates all required Legion channels with correct permissions.
> - **Example:** `/setup channels`
>
> ## ADMIN COMMANDS
>
> ### /admin force link
> - **Role:** Owner, Founder, Admin
> - **Description:** Force link someone's discord to their gamertag.
> - **Options:**  
>   - `@user` (required): Discord mention
>   - `gamertag` (required): Gamertag
> - **Expected Behaviour:** Binds Discord and gamertag forcibly.
> - **Example:** `/admin force link @user gamertag:Player1`
>
> ### /admin force unlink
> - **Role:** Owner, Founder, Admin
> - **Description:** Force unlink a member's discord from their gamertag.
> - **Options:**  
>   - `@user` (required): Discord mention
> - **Expected Behaviour:** Removes forced link.
> - **Example:** `/admin force unlink @user`
>
> ### /file gameplay damage
> - **Role:** Owner, Founder, Admin
> - **Description:** Turn base & container damage on/off on your server.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Toggles base damage.
> - **Example:** `/file gameplay damage enable:On`
>
> ### /admin getid
> - **Role:** Owner, Founder, Admin, Dev
> - **Description:** Get the discord ID of a member.
> - **Options:**  
>   - `@user` (required): Discord mention
> - **Expected Behaviour:** Returns user’s Discord ID.
> - **Example:** `/admin getid @user`
>
> ### /admin player search
> - **Role:** Owner, Founder, Admin, Dev
> - **Description:** Search for a gamertag or member.
> - **Options:**  
>   - `query` (required): Gamertag or username
> - **Expected Behaviour:** Returns info for user/gamertag.
> - **Example:** `/admin player search query:Player1`
>
> ### /admin spawner add
> - **Role:** Owner, Admin, Founder
> - **Description:** Build an event from discord.  
>   - Selection: Items/Static/Vehicle.  
>   - X Coord: XXXX (Not GPS).  
>   - Z Coord: ZZZZ.  
>   - Type Name: Item/Object/Vehicle from `types.xml`.  
>   - Lifetime: Seconds (permanent: 3888000).  
>   - Player Name: Event ref (no spaces).  
>   - Nominal/Max/Min: Spawn count.  
>   - Restock: Respawn delay (seconds).
> - **Options:** See description above
> - **Expected Behaviour:** Adds to events.xml for spawning items/vehicles.
> - **Example:** `/admin spawner add Selection:Vehicle X:1234 Z:5678 TypeName:Sedan Lifetime:3888000 PlayerName:Bob Nominal:1 Max:1 Min:1 Restock:0`
>
> ### /admin player locations
> - **Role:** Owner, Founder, Admin
> - **Description:** Current online player locations.
> - **Options:** None
> - **Expected Behaviour:** Shows all player coordinates.
> - **Example:** `/admin player locations`
>
> ### /admin force link
> - **Role:** Owner, Founder, Admin
> - **Description:** Force link someone's discord to their gamertag.
> - **Options:**  
>   - `@user` (required): Discord mention
>   - `gamertag` (required): Gamertag
> - **Expected Behaviour:** Links Discord user to gamertag.
> - **Example:** `/admin force link @user gamertag:Player1`
>
> ### /admin force unlink
> - **Role:** Owner, Founder, Admin
> - **Description:** Force unlink a member's discord from their gamertag.
> - **Options:**  
>   - `@user` (required): Discord mention
> - **Expected Behaviour:** Removes the link from database.
> - **Example:** `/admin force unlink @user`
>
> ### /wipe cars
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipes all cars, server restarts twice.
> - **Options:** None
> - **Expected Behaviour:** Removes all cars, restarts twice for clean spawn.
> - **Example:** `/wipe cars`
>
> ### /last locations
> - **Role:** Owner, Founder, Admin
> - **Description:** Last 20 locations for a gamertag.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Shows location history for player.
> - **Example:** `/last locations gamertag:Player1`
>
> ### /embed build
> - **Role:** Owner, Founder, Admin
> - **Description:** Send a message in an embed.
> - **Options:**  
>   - `message` (required): Embed message
> - **Expected Behaviour:** Posts a styled embed to the channel.
> - **Example:** `/embed build message:"Welcome!"`
>
> ### /logs auto download
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign a channel to auto-download logfiles every 4 hours.
> - **Options:**  
>   - `channel` (required): Discord channel
> - **Expected Behaviour:** Bot posts logs in the selected channel on schedule.
> - **Example:** `/logs auto download channel:#logs`
>
> ### /settings view
> - **Role:** Owner, Founder, Admin, Moderator
> - **Description:** View the settings for your server.
> - **Options:** None
> - **Expected Behaviour:** Displays all current Legion settings for this server.
> - **Example:** `/settings view`
>
> ### /settings configure name
> - **Role:** Owner, Founder, Admin
> - **Description:** Rename the server in the killfeed.
> - **Options:**  
>   - `name` (required): New server name
> - **Expected Behaviour:** Changes the server name in all killfeed outputs.
> - **Example:** `/settings configure name name:"New Server Name"`
>
> ### /settings configure glitchfeed
> - **Role:** Owner, Founder, Admin
> - **Description:** Allow flag logging of captured flags. Default is ON. Outputs flag logs to a dedicated channel.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Outputs flag logs to a dedicated channel.
> - **Example:** `/settings configure glitchfeed enable:On`
>
> ### /logs download current
> - **Role:** Owner, Founder, Admin
> - **Description:** Download current log file.
> - **Options:** None
> - **Expected Behaviour:** Sends the most recent log as a file.
> - **Example:** `/logs download current`
>
> ### /logs download all
> - **Role:** Owner, Founder, Admin
> - **Description:** Download all log files.
> - **Options:** None
> - **Expected Behaviour:** Sends all logs as a zip/attachments.
> - **Example:** `/logs download all`
>
> ### /logs download kills
> - **Role:** Owner, Founder, Admin
> - **Description:** Download current kills-only logfile.
> - **Options:** None
> - **Expected Behaviour:** Sends log containing only kill events.
> - **Example:** `/logs download kills`
>
> ### /server restart
> - **Role:** Owner, Founder, Admin
> - **Description:** Restart your server.
> - **Options:**  
>   - `server` (optional): Server to restart
> - **Expected Behaviour:** Initiates a Nitrado restart.
> - **Example:** `/server restart`
>
> ### /server stop
> - **Role:** Owner, Founder, Admin
> - **Description:** Stop your server.
> - **Options:**  
>   - `server` (optional): Server to stop
> - **Expected Behaviour:** Stops the Nitrado server.
> - **Example:** `/server stop`
>
> ### /server break loop
> - **Role:** Owner, Founder, Admin
> - **Description:** Break a restart loop for your server.
> - **Options:**  
>   - `server` (optional): Server to repair
> - **Expected Behaviour:** Attempts to recover the server from a stuck restart state.
> - **Example:** `/server break loop`
>
> ### /scheduler settings restarts
> - **Role:** Owner, Founder, Admin
> - **Description:** Auto restart your server if stopped for 10mins. If enabled, will automatically restart your server if it is found to be offline for 10+ minutes.
> - **Options:**  
>   - `state` (required): `{Active, Disabled}`
> - **Expected Behaviour:** Watches server state and starts if down >10min.
> - **Example:** `/scheduler settings restarts state:Active`
>
> ## BANNING, WHITELISTING & PRIORITY
>
> ### /ban add
> - **Role:** Owner, Founder, Admin
> - **Description:** Ban gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds to banlist; players cannot join.
> - **Example:** `/ban add gamertags:"Player1"`
>
> ### /ban remove
> - **Role:** Owner, Founder, Admin
> - **Description:** Unban gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from banlist.
> - **Example:** `/ban remove gamertags:"Player1"`
>
> ### /ban view
> - **Role:** Owner, Founder, Admin
> - **Description:** View banlist.
> - **Options:** None
> - **Expected Behaviour:** Shows current bans.
> - **Example:** `/ban view`
>
> ### /priority add
> - **Role:** Owner, Founder, Admin
> - **Description:** Prioritize gamertag/gamertags (queue skip).
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds player to priority join list.
> - **Example:** `/priority add gamertags:"Player1"`
>
> ### /priority remove
> - **Role:** Owner, Founder, Admin
> - **Description:** Unpriority gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from priority list.
> - **Example:** `/priority remove gamertags:"Player1"`
>
> ### /priority view
> - **Role:** Owner, Founder, Admin
> - **Description:** View priority list.
> - **Options:** None
> - **Expected Behaviour:** Shows all priority players.
> - **Example:** `/priority view`
>
> ### extra whitelist info (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin
> - **Description:** Whitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Whitelists user for info purposes.
> - **Example:** `extra whitelist info (current bot has no public slash command) gamertags:"Player1"`
>
> ### /whitelist add
> - **Role:** Owner, Founder, Admin
> - **Description:** Whitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds to whitelist; allows joining.
> - **Example:** `/whitelist add gamertags:"Player1"`
>
> ### /whitelist remove
> - **Role:** Owner, Founder, Admin
> - **Description:** Unwhitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from whitelist.
> - **Example:** `/whitelist remove gamertags:"Player1"`
>
> ### /whitelist view
> - **Role:** Owner, Founder, Admin
> - **Description:** View Whitelist.
> - **Options:** None
> - **Expected Behaviour:** Shows all currently whitelisted users.
> - **Example:** `/whitelist view`
>
> ### whitelist rebuild (current bot command is commented out)
> - **Role:** Owner, Founder, Admin
> - **Description:** Rebuild Whitelist.
> - **Options:** None
> - **Expected Behaviour:** Reprocesses the whitelist.
> - **Example:** `whitelist rebuild (current bot command is commented out)`
>
> ### whitelist upload (current bot command is commented out)
> - **Role:** Owner, Founder, Admin
> - **Description:** Upload a file to add gamertags to the whitelist.
> - **Options:**  
>   - `file` (required): whitelist.txt
> - **Expected Behaviour:** Bulk-imports whitelist entries.
> - **Example:** `whitelist upload (current bot command is commented out) file:whitelist.txt`
>
> ## SETTINGS COMMANDS
>
> ### /banking settings
> - **Role:** Owner, Founder, Admin
> - **Description:** All economy settings except bounties.  
>   Options: multiplier (required), max_bet, max_win, rob, daily, fish, work, rob_on_kill, earn_on_build
> - **Options:**  
>   - `multiplier` (required): Cash multiplier
>   - `max_bet` (optional): Maximum bet allowed
>   - `max_win` (optional): Maximum win allowed
>   - `rob` (optional): `{On, Off}`
>   - `daily` (optional): `{On, Off}`
>   - `fish` (optional): `{On, Off}`
>   - `work` (optional): `{On, Off}`
>   - `rob_on_kill` (optional): `{On, Off}`
>   - `earn_on_build` (optional): `{On, Off}`
> - **Expected Behaviour:** Updates money multipliers and toggles.
> - **Example:** `/banking settings multiplier:1 max_bet:1000 rob:On`
>
> ### /bounty admin min
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign your server's default bounty amount.
> - **Options:**  
>   - `minimum` (required): Bounty minimum
> - **Expected Behaviour:** Sets minimum bounty for your server.
> - **Example:** `/bounty admin min minimum:500`
>
> ### /settings configure linkrole
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign a role to be added when a player links.
> - **Options:**  
>   - `role` (required): Discord role
> - **Expected Behaviour:** Linked players get this role.
> - **Example:** `/settings configure linkrole role:@LinkedPlayer`
>
> ### /settings playersonline
> - **Role:** Owner, Founder, Admin
> - **Description:** Configure the players-online feature: assign text/voice channels, set the voice channel prefix, and enable location display.
> - **Options:**  
>   - `text` (optional): Text channel for online count posts
>   - `voice` (optional): Voice channel to display online count
>   - `voiceprefix` (optional): Prefix label for the voice channel (default: `On Now:`)
>   - `command` (optional): `{Enable, Disable}` — allow/disallow the public /plon command
>   - `txt_locations` (optional): `{On, Off}` — show player locations in text feed
> - **Expected Behaviour:** Updates players-online display settings for this server.
> - **Example:** `/settings playersonline text:#channel voice:#vc-channel voiceprefix:"On Now:"`
>
> ### /settings configure misc
> - **Role:** Owner, Founder, Admin
> - **Description:** Configure miscellaneous Legion Killfeed settings including auto-purge, log feed format, autostart, and players-online command access.
> - **Options:**  
>   - `purging` (optional): `{On, Off}` — auto-purge before posting Status, Heatmaps, Leaderboards
>   - `logfeed` (optional): `{.ADM, .txt}` — log file format for the admin log feed
>   - `autostart` (optional): `{On, Off}` — enable/disable bot autostart monitoring
>   - `allow_plon` (optional): `{Enable, Disable}` — allow/disallow the public /plon command
> - **Expected Behaviour:** Updates the selected misc settings for this server.
> - **Example:** `/settings configure misc purging:On logfeed:.ADM autostart:On allow_plon:Enable`
>
> ### /settings configure locations
> - **Role:** Owner, Founder, Admin
> - **Description:** Set per-feed location visibility in the killfeed. Each feed type can be individually toggled.
> - **Options:**  
>   - `killfeed` (optional): `{On, Off, Both, Near, No Link, Near No Link}`
>   - `pve` (optional): `{On, Off, Both, Near, No Link, Near No Link}`
>   - `hit` (optional): `{On, Off}`
>   - `build` (optional): `{On, Off}`
>   - `flag` (optional): `{On, Off}`
>   - `connect` (optional): `{On, Off}`
>   - `teleports` (optional): `{On, Off}`
>   - `uncons` (optional): `{On, Off}`
>   - `glitch` (optional): `{On, Off}`
>   - `spoiler` (optional): `{On, Off}`
>   - `players_online` (optional): `{On, Off}`
> - **Expected Behaviour:** Includes/excludes location data per feed type.
> - **Example:** `/settings configure locations killfeed:On pve:Both connect:Off`
>
> ### /settings channel assign
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign feed to channel or stop feed in channel.
> - **Options:**  
>   - `channel` (required): Discord channel
> - **Expected Behaviour:** Moves feed to new channel.
> - **Example:** `/settings channel assign channel:#pve-feed`
>
> ### /settings channel create
> - **Role:** Owner, Founder, Admin
> - **Description:** Add a channel from the list of channels for your selected server.
> - **Options:**  
>   - `name` (required): Channel name
> - **Expected Behaviour:** Creates and configures channel.
> - **Example:** `/settings channel create name:"hits-feed"`
>
> ### /settings configure logo
> - **Role:** Owner, Founder, Admin
> - **Description:** Add or remove a logo via URL for a selected server.
> - **Options:**  
>   - `url` (required): Image URL
> - **Expected Behaviour:** Logo will display on all embeds.
> - **Example:** `/settings configure logo url:"https://my.site/logo.png"`
>
>
> ## SCHEDULER
>
> ### /scheduler damage configure
> - **Role:** Owner, Founder, Admin
> - **Description:** Turn the automated base damage scheduler off.
> - **Options:** None
> - **Expected Behaviour:** Disables scheduled base damage.
> - **Example:** `/scheduler damage configure`
>
> ### /scheduler damage configure
> - **Role:** Owner, Founder, Admin
> - **Description:** Set the day, time, and timezone for base damage to be turned on.
> - **Options:**  
>   - `day` (required): Day of week
>   - `time` (required): Time (HH:MM)
>   - `timezone` (required): Timezone
> - **Expected Behaviour:** Turns ON base damage at scheduled time.
> - **Example:** `/scheduler damage configure day:Saturday time:16:00 timezone:AEST`
>
> ### /scheduler damage configure
> - **Role:** Owner, Founder, Admin
> - **Description:** Set the day, time, and timezone for base damage to be turned off.
> - **Options:**  
>   - `day` (required): Day of week
>   - `time` (required): Time (HH:MM)
>   - `timezone` (required): Timezone
> - **Expected Behaviour:** Turns OFF base damage at scheduled time.
> - **Example:** `/scheduler damage configure day:Sunday time:06:00 timezone:AEST`
>
> ## RESET STATS
>
> ### /wipe stats player
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipe a player's stats. [WARNING: This can't be undone!!!]
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** All stats reset for target player.
> - **Example:** `/wipe stats player gamertag:Player1`
>
> ### /wipe stats server
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipe a server's stats. [WARNING: This can't be undone!!!]
> - **Options:** None
> - **Expected Behaviour:** All server stats are reset.
> - **Example:** `/wipe stats server`
>
> ## AUTOBAN / WHITELIST
>
> ### /settings autoban config
> - **Role:** Admin or Higher
> - **Description:** Autoban whole map on kill or death, or on swimming (Coords Height = below 0).
> - **Options:**  
>   - `mode` (required): `{OnKill, OnDeath, Off}`
> - **Expected Behaviour:** Bans any player who triggers config.
> - **Example:** `/settings autoban config mode:OnKill`
>
> ### /settings autoban whitelist
> - **Role:** Admin or Higher
> - **Description:** Add/Remove/View whitelisted gamertags for autoban.
> - **Options:**  
>   - `action` (required): `{add, remove, view}`
>   - `gamertag` (optional): Player's gamertag
> - **Expected Behaviour:** Excludes player(s) from autoban logic.
> - **Example:** `/settings autoban whitelist add gamertag:Player1`
>
> ## WEBINTERFACE
>
> ### /nitrado dashboard settings
> - **Role:** Admin or Higher
> - **Description:** Update options on Nitrado's web interface.
> - **Options:**  
>   - `setting` (required): Setting to update
>   - `value` (required): New value
> - **Expected Behaviour:** Applies change to Nitrado web interface.
> - **Example:** `/nitrado dashboard settings setting:restart value:03:00`
>
> ### /file upload
> - **Role:** Admin or Higher
> - **Description:** Upload file to folder on your server.
> - **Options:**  
>   - `file` (required): Filename
>   - `folder` (required): Folder path
> - **Expected Behaviour:** Uploads file to server.
> - **Example:** `/file upload file:"myfile.txt" folder:"/config/"`
>
> ### /file download
> - **Role:** Admin or Higher
> - **Description:** Download file from any folder on your server.
> - **Options:**  
>   - `file` (required): Filename
>   - `folder` (required): Folder path
> - **Expected Behaviour:** Downloads file from server.
> - **Example:** `/file download file:spawner_data folder:/config/`
>
> ### /nitrado details update
> - **Role:** Admin or Higher
> - **Description:** Edits the server’s name and descriptive info on Nitrado and optionally adds invisible boost character.
> - **Options:**  
>   - `name` (required): Server's New Name
>   - `description` (required): Server's description
>   - `boost` (required): Add invisible boost character (Yes or No)
>   - `restart` (required): On/Off
> - **Expected Behaviour:** Update's options on Nitrado and sends embed showing current server name, description, boost status.
> - **Example:** `/nitrado details update name:"New Server" description:"PvP Focused" boost:On restart:Off`
>
> ### /nitrado details view
> - **Role:** Admin or Higher
> - **Description:** View the server’s name and descriptive info on Nitrado and if it uses invisible boost character.
> - **Options:** Dropdown - Select Server
> - **Expected Behaviour:** Sends embed showing current server name, description, boost status.
> - **Example:** `/nitrado details view`
>
> ### /heatmaps
> - **Role:** Owner, Founder, Admin
> - **Description:** Heatmaps of player kills or player locations.
> - **Options:**  
>   - `type` (required): `{Kills, Damage, Locations, Pinmap, Usage}`
> - **Expected Behaviour:** Generates and posts a heatmap image.
> - **Example:** `/heatmaps type:Kills`
>
> ## BOUNTY ADMIN
>
> ### /bounty admin pay
> - **Role:** Admin
> - **Description:** Pay a bounty, either your own or someone else's bounty without using your balance.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Pays off a posted bounty.
> - **Example:** `/bounty admin pay gamertag:LegionKillfeed`
>
> ### /bounty admin clean
> - **Role:** Admin
> - **Description:** Clean all inactive bounties in X timeframe.
> - **Options:**  
>   - `timeframe` (required): 10 days - Over 90 days
> - **Expected Behaviour:** Sets the bounty for all accounts outside time frame to 0.
> - **Example:** `/bounty admin clean timeframe:70days`
>
> ## ECONOMY ADMIN
>
> ### /banking adjust user
> - **Role:** Admin
> - **Description:** Give or remove money from a specific Discord member’s account.
> - **Options:**  
>   - `toggle` (required): `{Add, Remove}`
>   - `balance` (required): Amount
>   - `member` (required): Discord @mention
>   - `account` (required): `{Cash, Bank}`
> - **Expected Behaviour:** Adjusts the selected account balance for the specified member.
> - **Example:** `/banking adjust user toggle:Add balance:1000 member:@User account:Cash`
>
> ### /banking adjust all
> - **Role:** Admin
> - **Description:** Give or remove money from all linked accounts.
> - **Options:**  
>   - `toggle` (required): `{Add, Remove}`
>   - `amount` (required): Amount
>   - `account` (required): `{Cash, Bank}`
> - **Expected Behaviour:** Adjusts all linked account balances simultaneously.
> - **Example:** `/banking adjust all toggle:Add amount:1000 account:Cash`
>
> ### /banking manage reset
> - **Role:** Admin
> - **Description:** Wipe all money accounts.
> - **Options:** None
> - **Expected Behaviour:** All cash/bank reset.
> - **Example:** `/banking manage reset`
>
> ### /banking settings
> - **Role:** Admin
> - **Description:** Assign default balances.
> - **Options:**  
>   - `balance` (required): Default balance
> - **Expected Behaviour:** Sets all balances to default.
> - **Example:** `/banking settings balance:1000`
>
> ## TICKETS
>
> ### /ticket close
> - **Role:** Owner, Founder, Admin
> - **Description:** Close a thread.
> - **Options:** None
> - **Expected Behaviour:** Closes ticket.
> - **Example:** `/ticket close`
>
> ### /ticket setup
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign design for ticket panel for active servers.
> - **Options:**  
>   - `design` (required): Design name
> - **Expected Behaviour:** Sets ticket panel design.
> - **Example:** `/ticket setup design:"Modern"`
>
> ### /ticket setup
> - **Role:** Owner, Founder, Admin
> - **Description:** Style your tickets for active servers.
> - **Options:**  
>   - `style` (required): Style name
> - **Expected Behaviour:** Sets ticket style.
> - **Example:** `/ticket setup style:"Dark"`
>
> ### /ticket setup
> - **Role:** Owner, Founder, Admin
> - **Description:** Style your ticket welcome embed for active servers.
> - **Options:**  
>   - `message` (required): Welcome text
> - **Expected Behaviour:** Sets welcome text.
> - **Example:** `/ticket setup message:"Welcome to Support"`
>
> ### /ticket colours
> - **Role:** Owner, Founder, Admin
> - **Description:** See what colours we have available for embeds.
> - **Options:** None
> - **Expected Behaviour:** Shows colour options.
> - **Example:** `/ticket colours`
>
> ### /ticket refresh
> - **Role:** Owner, Founder, Admin
> - **Description:** Re-post ticket embeds.
> - **Options:** None
> - **Expected Behaviour:** Refreshes all tickets.
> - **Example:** `/ticket refresh`
>
> ### /ticket setup
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign ticket role and create ticket category and channels.
> - **Options:**  
>   - `role` (required): Discord role
> - **Expected Behaviour:** Sets up support system.
> - **Example:** `/ticket setup role:@Support`
>
> ## VALIDATION
>
> ### /compare updates
> - **Role:** Owner, Founder, Admin
> - **Description:** Compare your files with the latest version and get a list of updates.
> - **Options:** None
> - **Expected Behaviour:** Shows update info.
> - **Example:** `/compare updates`
>
> ### /compare
> - **Role:** Owner, Founder, Admin
> - **Description:** Compare your files with the latest version.
> - **Options:** None
> - **Expected Behaviour:** Shows file diff.
> - **Example:** `/compare`
>
> ## TYPES.XML TOOLS
>
> ### /types local validate
> - **Role:** Owner, Founder, Admin
> - **Description:** Validate Local XML file.
> - **Options:**  
>   - `file` (required): XML file
> - **Expected Behaviour:** Checks for errors.
> - **Example:** `/types local validate file:types.xml`
>
> ### /types local boost
> - **Role:** Owner, Founder, Admin
> - **Description:** Mass boost all nominals and mins to x amount.
> - **Options:**  
>   - `boost` (required): Amount
> - **Expected Behaviour:** Updates values.
> - **Example:** `/types local boost boost:1000`
>
> ### /types local edit
> - **Role:** Owner, Founder, Admin
> - **Description:** Bulk Edit Local Types.XML file by category, tag, usage, or value.
> - **Options:**  
>   - `tag` (optional): Tag/category
>   - `value` (optional): Value to set
> - **Expected Behaviour:** Updates all matching entries.
> - **Example:** `/types local edit tag:food value:10`
>
> ### /types server boost
> - **Role:** Owner, Founder, Admin
> - **Description:** Mass boost all nominals and mins to x amount.
> - **Options:**  
>   - `boost` (required): Amount
> - **Expected Behaviour:** Updates values on server.
> - **Example:** `/types server boost boost:1000`
>
> ## BASE RADARS
>
> ### base radar setup (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin
> - **Description:** Create a base radar of maximum 999metres.  
>   X/Z: map coords; Radius: <=999m; Zone Name, Owner, Channel, Role, Ban actions, etc.
> - **Options:**  
>   - `x` (required): X coord
>   - `z` (required): Z coord
>   - `radius` (required): Radius
>   - `name` (required): Zone name
>   - `owner` (required): Zone owner
>   - ...plus ban/action toggles
> - **Expected Behaviour:** Creates area/radar for notifications or autoban.
> - **Example:** `base radar setup (current bot has no public slash command) x:1234 z:5678 radius:500 name:"Red Zone"`
>
> ### base radar edit (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin
> - **Description:** Edit an existing base radar.
> - **Options:**  
>   - `id` (required): Radar ID
>   - ...other editable options
> - **Expected Behaviour:** Updates area or settings.
> - **Example:** `base radar edit (current bot has no public slash command) id:3 radius:999`
>
> ### base radar delete (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin
> - **Description:** Delete a base radar.
> - **Options:**  
>   - `id` (required): Radar ID
> - **Expected Behaviour:** Removes area.
> - **Example:** `base radar delete (current bot has no public slash command) id:3`
>
> ### base radar list (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin
> - **Description:** Get list of a base radars.
> - **Options:** None
> - **Expected Behaviour:** Lists all radar zones.
> - **Example:** `base radar list (current bot has no public slash command)`

---

> # ANY USER/PLAYER
> ## LINKING
> ### /link
> - **Role:** `@everyone`
> - **Description:** Link your discord to your gamertag.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Connects your Discord and gamertag in the system.
> - **Example:** `/link gamertag:Player1`
> ### /unlink
> - **Role:** `@everyone`
> - **Description:** Unlink your discord from your gamertag.
> - **Options:** None
> - **Expected Behaviour:** Removes link.
> - **Example:** `/unlink`
>
> ## BASE RADARS
>
> ### base radar ignore add (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Add gamertag/gamertags to base radar ignore.  
>   **Must be used in radar channel.**
> - **Options:**  
>   - `gamertag` (required): Gamertag(s)
> - **Expected Behaviour:** Player(s) are ignored by radar.
> - **Example:** `base radar ignore add (current bot has no public slash command) gamertag:Player1`
>
> ### base radar ignore remove (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Remove gamertag/gamertags from base radar ignore.  
>   **Must be used in radar channel.**
> - **Options:**  
>   - `gamertag` (required): Gamertag(s)
> - **Expected Behaviour:** Player(s) no longer ignored.
> - **Example:** `base radar ignore remove (current bot has no public slash command) gamertag:Player1`
>
> ### base radar ignore info (current bot has no public slash command)
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Lists base radar details.  
>   **Must be used in radar channel.**
> - **Options:** None
> - **Expected Behaviour:** Shows current radar config.
> - **Example:** `base radar ignore info (current bot has no public slash command)`
>
> ## STATS
>
> ### /stats
>
> - **Role:** `@everyone`
> - **Description:** Get stats for your selected server.
> - **Options:**
>   - `gamertag` (optional): Player's gamertag or @USER or None
> - **Expected Behaviour:** Shows your/someone else stats.
> - **Example:** `/stats @Soul`
>
> ### /mine
>
> - **Role:** `@everyone`
> - **Description:** Get stats for your selected server.
> - **Options:** None
> - **Expected Behaviour:** Shows your stats.
> - **Example:** `/mine`
>
> ### /global
> - **Role:** `@everyone`
> - **Description:** Global leaderboards.
> - **Options:** None
> - **Expected Behaviour:** Shows stats across all servers.
> - **Example:** `/global`
>
> ### /leaderboard
> - **Role:** `@everyone`
> - **Description:** Server's Leaderboard.
> - **Options:** None
> - **Expected Behaviour:** Ranks by kills.
> - **Example:** `/leaderboard`
>
> ### /locate
> - **Role:** `@everyone`
> - **Description:** DM linked player their last logged location.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Sends last location in DMs.
> - **Example:** `/locate gamertag:Player1`
>
> ## BOUNTY
>
> ### /bounty view
> - **Role:** `@everyone`
> - **Description:** View server's bounty list.
> - **Options:** None
> - **Expected Behaviour:** Shows all current bounties.
> - **Example:** `/bounty view`
>
> ### /bounty pay
> - **Role:** `@everyone`
> - **Description:** Pay a bounty, either your own or someone else's.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Pays off a posted bounty.
> - **Example:** `/bounty pay gamertag:LegionKillfeed`
>
> ### /bounty add
> - **Role:** `@everyone`
> - **Description:** Add a bounty to someone.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
>   - `amount` (required): Amount
> - **Expected Behaviour:** Posts bounty for player.
> - **Example:** `/bounty add gamertag:Player1 amount:500`
>
> ## BANKING
>
> ### /bal
> - **Role:** `@everyone`
> - **Description:** Check your balance.
>   - `user` (optional): @USER or None
> - **Expected Behaviour:** Shows your cash and bank balance or a linked user's balance.
> - **Example:** `/bal`
>
> ### /deposit
> - **Role:** `@everyone`
> - **Description:** Deposit money to your bank.
> - **Options:**  
>   - `amount` (required): Amount
> - **Expected Behaviour:** Adds to your bank, deducts from cash.
> - **Example:** `/deposit amount:1000`
>
> ### /withdraw
> - **Role:** `@everyone`
> - **Description:** Withdraw money from your related server's bank.
> - **Options:**  
>   - `amount` (required): Amount
> - **Expected Behaviour:** Moves bank to cash.
> - **Example:** `/withdraw amount:500`
>
> ### /pay
> - **Role:** `@everyone` (Must have played server)
> - **Description:** Pay someone.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
>   - `amount` (required): Amount
> - **Expected Behaviour:** Transfers cash.
> - **Example:** `/pay gamertag:Player1 amount:500`
>
> ## EARNING
>
> ### /rob
> - **Role:** `@everyone`
> - **Description:** Rob up to 50% of cash from another user.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Steals cash if successful.
> - **Example:** `/rob gamertag:Player1`
>
> ### /fish
> - **Role:** `@everyone`
> - **Description:** Go fishing to earn money.
> - **Options:** None
> - **Expected Behaviour:** Random cash reward.
> - **Example:** `/fish`
>
> ### /work
> - **Role:** `@everyone`
> - **Description:** Work to earn money.
> - **Options:** None
> - **Expected Behaviour:** Random cash reward.
> - **Example:** `/work`
>
> ### /daily
> - **Role:** `@everyone`
> - **Description:** Claim your daily reward.
> - **Options:** None
> - **Expected Behaviour:** One daily payout.
> - **Example:** `/daily`
>
> ## GAMBLING
>
> ### /slots
> - **Role:** `@everyone`
> - **Description:** Play slots.
> - **Options:**
>   - `bet` (required): Amount
> - **Expected Behaviour:** Gamble for cash.
> - **Example:** `/slots`
>
> ### /blackjack
> - **Role:** `@everyone`
> - **Description:** Play a game of blackjack.
> - **Options:** 
>   - `bet` (required): Amount
> - **Expected Behaviour:** Gamble for cash.
> - **Example:** `/blackjack`
>
> ### /diceroll
> - **Role:** `@everyone`
> - **Description:** Play a dice roll game.
> - **Options:** 
>   - `bet` (required): Amount
>   - `1-6` (required): Side of dice to bet on
> - **Expected Behaviour:** Gamble for cash.
> - **Example:** `/diceroll`
>
> ### /roulette
> - **Role:** `@everyone`
> - **Description:** Play a roulette game.
> - **Options:**
>   - `bet` (required): Amount
>   - `color` (optional): Bet on black or red
>   - `number` (optional): Bet on a number (0-36)
>   - `vthirds` (optional): Bet on vertical thirds 1-12, 13-24 or 25-36
>   - `hthirds` (optional): Bet on horizontal thirds 1-34, 2-35 or 3-36
>   - `parity` (optional): Bet on even or odd
>   - `halves` (optional): Bet on table half 1-18 or 19-36
> - **Expected Behaviour:** Gamble for cash.
> - **Example:** `/roulette`
>
> ### /rps
> - **Role:** `@everyone`
> - **Description:** Play a game of rock-paper-scissors.
> - **Options:**
>   - `bet` (required): Amount
>   - `rock, paper or scissors` (required): Choose rock, paper or scissors to bet on
> - **Expected Behaviour:** Gamble for cash.
> - **Example:** `/rps`
>
> ## MISC
>
> ### /plon
> - **Role:** `@everyone`
> - **Description:** Players online. Reply is slow for accuracy.
> - **Options:** None
> - **Expected Behaviour:** Shows player count.
> - **Example:** `/plon`
>
> ### /submit bot suggestions
> - **Role:** `@everyone`
> - **Description:** Submit a bug report to the developers.
> - **Options:**  
>   - `description` (required): Bug details
> - **Expected Behaviour:** Sends report to devs.
> - **Example:** `/submit bot suggestions description:"Bug description"`
>
> ### /godmode
> - **Role:** `@everyone`
> - **Description:** A fake God Mode command for the lols.
> - **Options:** None
> - **Expected Behaviour:** "Activates" godmode (joke).
> - **Example:** `/godmode user:@User`
>
> ### /fight
> - **Role:** `@everyone`
> - **Description:** Challenge a user to a fight; loser is timed out.
> - **Options:**  
>   - `@user` (required): Discord mention
> - **Expected Behaviour:** Loser is temp muted.
> - **Example:** `/fight @user`
>
> ### /last restart
> - **Role:** `@everyone`
> - **Description:** Get the last restart, next restart, and current players online.
> - **Options:** None
> - **Expected Behaviour:** Shows restart times and online count.
> - **Example:** `/last restart`
>
> ### /submit bot suggestions
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Suggestion/Request. Sends suggestion to Legion staff for review.
> - **Options:**  
>   - `message` (required): Suggestion text
> - **Expected Behaviour:** Submits suggestion to staff for review.
> - **Example:** `/submit bot suggestions message:"Add a new feature"`
>
> ### /submit bot roast
> - **Role:** `@everyone`
> - **Description:** Submit Roasts To Legion Killfeed.
> - **Options:**  
>   - `message` (required): Roast text
> - **Expected Behaviour:** Sends roast to staff for possible use as death message in embeds..
> - **Example:** `/submit bot roast message:"{USER} is slower than my grandma’s dial-up!"`
>
> ## HELP AND INFO
>
> ### /help
> - **Role:** `@everyone`
> - **Description:** Select a category to view help commands.
> - **Options:**  
>   - `category` (required): Category name
> - **Expected Behaviour:** Displays help for category.
> - **Example:** `/help category:Economy`
>
> ### /info
> - **Role:** `@everyone`
> - **Description:** Bot information.
> - **Options:** None
> - **Expected Behaviour:** Shows Legion Killfeed info and stats.
> - **Example:** `/info`
>
> ### /info
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Advertisement.
> - **Options:** None
> - **Expected Behaviour:** Posts promo/invite.
> - **Example:** `/info`
>
> ### /killfeed support
> - **Role:** `@everyone`
> - **Description:** Get a discord invite to Legion Killfeeds Support discord.
> - **Options:** None
> - **Expected Behaviour:** Posts support server invite.
> - **Example:** `/killfeed support`
>
> ### /subscribe
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Premium Subscription Price.
> - **Options:** None
> - **Expected Behaviour:** Shows premium pricing.
> - **Example:** `/subscribe`
>
> ### /banking help
> - **Role:** `@everyone`
> - **Description:** View the list of commands and a brief description.
> - **Options:** None
> - **Expected Behaviour:** Shows all economy commands.
> - **Example:** `/banking help`
>
> ### /banking leaderboard
> - **Role:** `@everyone`
> - **Description:** Economy leaderboard. Linked members only.
> - **Options:** None
> - **Expected Behaviour:** Shows cash rankings.
> - **Example:** `/banking leaderboard`
>
