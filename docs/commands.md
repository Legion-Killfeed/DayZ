**Legion Killfeed – Full Commands**

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
> ### /base damage
> - **Role:** Owner, Founder, Admin
> - **Description:** Turn base & container damage on/off on your server.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Toggles base damage.
> - **Example:** `/base damage enable:On`
>
> ### /admin getid
> - **Role:** Owner, Founder, Admin, Dev
> - **Description:** Get the discord ID of a member.
> - **Options:**  
>   - `@user` (required): Discord mention
> - **Expected Behaviour:** Returns user’s Discord ID.
> - **Example:** `/admin getid @user`
>
> ### /admin search
> - **Role:** Owner, Founder, Admin, Dev
> - **Description:** Search for a gamertag or member.
> - **Options:**  
>   - `query` (required): Gamertag or username
> - **Expected Behaviour:** Returns info for user/gamertag.
> - **Example:** `/admin search query:Player1`
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
> ### /admin plocs
> - **Role:** Owner, Founder, Admin
> - **Description:** Current online player locations.
> - **Options:** None
> - **Expected Behaviour:** Shows all player coordinates.
> - **Example:** `/admin plocs`
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
> ### /car_wipe
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipes all cars, server restarts twice.
> - **Options:** None
> - **Expected Behaviour:** Removes all cars, restarts twice for clean spawn.
> - **Example:** `/car_wipe`
>
> ### /last locations
> - **Role:** Owner, Founder, Admin
> - **Description:** Last 20 locations for a gamertag.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** Shows location history for player.
> - **Example:** `/last locations gamertag:Player1`
>
> ### /legion embed
> - **Role:** Owner, Founder, Admin
> - **Description:** Send a message in an embed.
> - **Options:**  
>   - `message` (required): Embed message
> - **Expected Behaviour:** Posts a styled embed to the channel.
> - **Example:** `/legion embed message:"Welcome!"`
>
> ### /logs autofeed
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign a channel to auto-download logfiles every 4 hours.
> - **Options:**  
>   - `channel` (required): Discord channel
> - **Expected Behaviour:** Bot posts logs in the selected channel on schedule.
> - **Example:** `/logs autofeed channel:#logs`
>
> ### /settings view
> - **Role:** Owner, Founder, Admin, Moderator
> - **Description:** View the settings for your server.
> - **Options:** None
> - **Expected Behaviour:** Displays all current Legion settings for this server.
> - **Example:** `/settings view`
>
> ### /settings rename
> - **Role:** Owner, Founder, Admin
> - **Description:** Rename the server in the killfeed.
> - **Options:**  
>   - `name` (required): New server name
> - **Expected Behaviour:** Changes the server name in all killfeed outputs.
> - **Example:** `/settings rename name:"New Server Name"`
>
> ### /settings flag_logs
> - **Role:** Owner, Founder, Admin
> - **Description:** Allow flag logging of captured flags. Default is ON. Outputs flag logs to a dedicated channel.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Outputs flag logs to a dedicated channel.
> - **Example:** `/settings flag_logs enable:On`
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
> ### /legion restart
> - **Role:** Owner, Founder, Admin
> - **Description:** Restart your server.
> - **Options:**  
>   - `server` (optional): Server to restart
> - **Expected Behaviour:** Initiates a Nitrado restart.
> - **Example:** `/legion restart`
>
> ### /legion stop
> - **Role:** Owner, Founder, Admin
> - **Description:** Stop your server.
> - **Options:**  
>   - `server` (optional): Server to stop
> - **Expected Behaviour:** Stops the Nitrado server.
> - **Example:** `/legion stop`
>
> ### /legion restartloop
> - **Role:** Owner, Founder, Admin
> - **Description:** Break a restart loop for your server.
> - **Options:**  
>   - `server` (optional): Server to repair
> - **Expected Behaviour:** Attempts to recover the server from a stuck restart state.
> - **Example:** `/legion restartloop`
>
> ### /legion autostart
> - **Role:** Owner, Founder, Admin
> - **Description:** Auto restart your server if stopped for 10mins. If enabled, will automatically restart your server if it is found to be offline for 10+ minutes.
> - **Options:**  
>   - `choice` (required): `{On, Off}`
> - **Expected Behaviour:** Watches server state and starts if down >10min.
> - **Example:** `/legion autostart choice:On`
>
> ## BANNING, WHITELISTING & PRIORITY
>
> ### /add ban
> - **Role:** Owner, Founder, Admin
> - **Description:** Ban gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds to banlist; players cannot join.
> - **Example:** `/add ban gamertags:"Player1"`
>
> ### /remove ban
> - **Role:** Owner, Founder, Admin
> - **Description:** Unban gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from banlist.
> - **Example:** `/remove ban gamertags:"Player1"`
>
> ### /view bans
> - **Role:** Owner, Founder, Admin
> - **Description:** View banlist.
> - **Options:** None
> - **Expected Behaviour:** Shows current bans.
> - **Example:** `/view bans`
>
> ### /add priority
> - **Role:** Owner, Founder, Admin
> - **Description:** Prioritize gamertag/gamertags (queue skip).
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds player to priority join list.
> - **Example:** `/add priority gamertags:"Player1"`
>
> ### /remove priority
> - **Role:** Owner, Founder, Admin
> - **Description:** Unpriority gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from priority list.
> - **Example:** `/remove priority gamertags:"Player1"`
>
> ### /view priority
> - **Role:** Owner, Founder, Admin
> - **Description:** View priority list.
> - **Options:** None
> - **Expected Behaviour:** Shows all priority players.
> - **Example:** `/view priority`
>
> ### /add info_whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** Whitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Whitelists user for info purposes.
> - **Example:** `/add info_whitelist gamertags:"Player1"`
>
> ### /add whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** Whitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Adds to whitelist; allows joining.
> - **Example:** `/add whitelist gamertags:"Player1"`
>
> ### /remove whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** Unwhitelist gamertag/gamertags.
> - **Options:**  
>   - `gamertags` (required): Comma-separated list
> - **Expected Behaviour:** Removes from whitelist.
> - **Example:** `/remove whitelist gamertags:"Player1"`
>
> ### /view whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** View Whitelist.
> - **Options:** None
> - **Expected Behaviour:** Shows all currently whitelisted users.
> - **Example:** `/view whitelist`
>
> ### /remove rebuild_whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** Rebuild Whitelist.
> - **Options:** None
> - **Expected Behaviour:** Reprocesses the whitelist.
> - **Example:** `/remove rebuild_whitelist`
>
> ### /add upload_whitelist
> - **Role:** Owner, Founder, Admin
> - **Description:** Upload a file to add gamertags to the whitelist.
> - **Options:**  
>   - `file` (required): whitelist.txt
> - **Expected Behaviour:** Bulk-imports whitelist entries.
> - **Example:** `/add upload_whitelist file:whitelist.txt`
>
> ## SETTINGS COMMANDS
>
> ### /settings economy
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
> - **Example:** `/settings economy multiplier:1 max_bet:1000 rob:On`
>
> ### /settings bounty
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign your server's default bounty amount.
> - **Options:**  
>   - `minimum` (required): Bounty minimum
> - **Expected Behaviour:** Sets minimum bounty for your server.
> - **Example:** `/settings bounty minimum:500`
>
> ### /settings linked role
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign a role to be added when a player links.
> - **Options:**  
>   - `role` (required): Discord role
> - **Expected Behaviour:** Linked players get this role.
> - **Example:** `/settings linked role role:@LinkedPlayer`
>
> ### /settings plon
> - **Role:** Owner, Founder, Admin
> - **Description:** Enable/Disable /plon (players online) command.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Allows/disallows public online count.
> - **Example:** `/settings plon enable:On`
>
> ### /settings set_plon_prefix
> - **Role:** Owner, Founder, Admin
> - **Description:** Change the start of your player count.
> - **Options:**  
>   - `prefix` (required): Text
> - **Expected Behaviour:** Changes prefix for `/plon` output.
> - **Example:** `/settings set_plon_prefix prefix:"Online:"`
>
> ### /settings feeds clean
> - **Role:** Owner, Founder, Admin
> - **Description:** Enable/Disable purge messages for Status, Heatmaps, Leaderboards.
> - **Options:**  
>   - `clean` (required): `{On, Off}`
> - **Expected Behaviour:** Bot purges feed messages after a period.
> - **Example:** `/settings feeds clean clean:On`
>
> ### /settings locations
> - **Role:** Owner, Founder, Admin
> - **Description:** Turn locations on/off in the killfeed.
> - **Options:**  
>   - `enable` (required): `{On, Off}`
> - **Expected Behaviour:** Includes/excludes locations in output.
> - **Example:** `/settings locations enable:On`
>
> ### /settings channels assign
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign feed to channel or stop feed in channel.
> - **Options:**  
>   - `channel` (required): Discord channel
> - **Expected Behaviour:** Moves feed to new channel.
> - **Example:** `/settings channels assign channel:#pve-feed`
>
> ### /settings channels create
> - **Role:** Owner, Founder, Admin
> - **Description:** Add a channel from the list of channels for your selected server.
> - **Options:**  
>   - `name` (required): Channel name
> - **Expected Behaviour:** Creates and configures channel.
> - **Example:** `/settings channels create name:"hits-feed"`
>
> ### /settings add logo
> - **Role:** Owner, Founder, Admin
> - **Description:** Add or remove a logo via URL for a selected server.
> - **Options:**  
>   - `url` (required): Image URL
> - **Expected Behaviour:** Logo will display on all embeds.
> - **Example:** `/settings add logo url:"https://my.site/logo.png"`
>
> ### /settings admin roles
> - **Role:** Owner, Founder, Admin
> - **Description:** Add killfeed permission to a discord role from a list of permissions.
> - **Options:**  
>   - `role` (required): Discord role
> - **Expected Behaviour:** Role can now use admin commands.
> - **Example:** `/settings admin roles role:@Admin`
>
> ## SCHEDULER
>
> ### /schedule damage stop
> - **Role:** Owner, Founder, Admin
> - **Description:** Turn the automated base damage scheduler off.
> - **Options:** None
> - **Expected Behaviour:** Disables scheduled base damage.
> - **Example:** `/schedule damage stop`
>
> ### /schedule damage enabled
> - **Role:** Owner, Founder, Admin
> - **Description:** Set the day, time, and timezone for base damage to be turned on.
> - **Options:**  
>   - `day` (required): Day of week
>   - `time` (required): Time (HH:MM)
>   - `timezone` (required): Timezone
> - **Expected Behaviour:** Turns ON base damage at scheduled time.
> - **Example:** `/schedule damage enabled day:Saturday time:16:00 timezone:AEST`
>
> ### /schedule damage disabled
> - **Role:** Owner, Founder, Admin
> - **Description:** Set the day, time, and timezone for base damage to be turned off.
> - **Options:**  
>   - `day` (required): Day of week
>   - `time` (required): Time (HH:MM)
>   - `timezone` (required): Timezone
> - **Expected Behaviour:** Turns OFF base damage at scheduled time.
> - **Example:** `/schedule damage disabled day:Sunday time:06:00 timezone:AEST`
>
> ## RESET STATS
>
> ### /reset stats player
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipe a player's stats. [WARNING: This can't be undone!!!]
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
> - **Expected Behaviour:** All stats reset for target player.
> - **Example:** `/reset stats player gamertag:Player1`
>
> ### /reset stats server
> - **Role:** Owner, Founder, Admin
> - **Description:** Wipe a server's stats. [WARNING: This can't be undone!!!]
> - **Options:** None
> - **Expected Behaviour:** All server stats are reset.
> - **Example:** `/reset stats server`
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
> ### /webinterface update
> - **Role:** Admin or Higher
> - **Description:** Update options on Nitrado's web interface.
> - **Options:**  
>   - `setting` (required): Setting to update
>   - `value` (required): New value
> - **Expected Behaviour:** Applies change to Nitrado web interface.
> - **Example:** `/webinterface update setting:restart value:03:00`
>
> ### /webinterface upload
> - **Role:** Admin or Higher
> - **Description:** Upload file to folder on your server.
> - **Options:**  
>   - `file` (required): Filename
>   - `folder` (required): Folder path
> - **Expected Behaviour:** Uploads file to server.
> - **Example:** `/webinterface upload file:"myfile.txt" folder:"/config/"`
>
> ### /webinterface download
> - **Role:** Admin or Higher
> - **Description:** Download file from any folder on your server.
> - **Options:**  
>   - `file` (required): Filename
>   - `folder` (required): Folder path
> - **Expected Behaviour:** Downloads file from server.
> - **Example:** `/webinterface download file:spawner_data folder:/config/`
>
> ### /server details edit
> - **Role:** Admin or Higher
> - **Description:** Edits the server’s name and descriptive info on Nitrado and optionally adds invisible boost character.
> - **Options:**  
>   - `name` (required): Server's New Name
>   - `description` (required): Server's description
>   - `boost` (required): Add invisible boost character (Yes or No)
>   - `restart` (required): On/Off
> - **Expected Behaviour:** Update's options on Nitrado and sends embed showing current server name, description, boost status.
> - **Example:** `/server details edit name:"New Server" description:"PvP Focused" boost:On restart:Off`
>
> ### /server details view
> - **Role:** Admin or Higher
> - **Description:** View the server’s name and descriptive info on Nitrado and if it uses invisible boost character.
> - **Options:** Dropdown - Select Server
> - **Expected Behaviour:** Sends embed showing current server name, description, boost status.
> - **Example:** `/server details view`
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
> ### /economy amoney user
> - **Role:** Admin
> - **Description:** Give or remove money from a user's account.
> - **Options:**  
>   - `gamertag` (required): Player's gamertag
>   - `amount` (required): Amount
> - **Expected Behaviour:** Modifies player’s balance.
> - **Example:** `/economy amoney user gamertag:Player1 amount:1000`
>
> ### /economy amoney all
> - **Role:** Admin
> - **Description:** Give or remove money from all linked accounts.
> - **Options:**  
>   - `amount` (required): Amount
> - **Expected Behaviour:** Updates all balances.
> - **Example:** `/economy amoney all amount:1000`
>
> ### /economy amoney reset
> - **Role:** Admin
> - **Description:** Wipe all money accounts.
> - **Options:** None
> - **Expected Behaviour:** All cash/bank reset.
> - **Example:** `/economy amoney reset`
>
> ### /economy amoney default
> - **Role:** Admin
> - **Description:** Assign default balances.
> - **Options:**  
>   - `balance` (required): Default balance
> - **Expected Behaviour:** Sets all balances to default.
> - **Example:** `/economy amoney default balance:1000`
>
> ## TICKETS
>
> ### /tickets close
> - **Role:** Owner, Founder, Admin
> - **Description:** Close a thread.
> - **Options:** None
> - **Expected Behaviour:** Closes ticket.
> - **Example:** `/tickets close`
>
> ### /tickets panel
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign design for ticket panel for active servers.
> - **Options:**  
>   - `design` (required): Design name
> - **Expected Behaviour:** Sets ticket panel design.
> - **Example:** `/tickets panel design:"Modern"`
>
> ### /tickets style
> - **Role:** Owner, Founder, Admin
> - **Description:** Style your tickets for active servers.
> - **Options:**  
>   - `style` (required): Style name
> - **Expected Behaviour:** Sets ticket style.
> - **Example:** `/tickets style style:"Dark"`
>
> ### /tickets welcome
> - **Role:** Owner, Founder, Admin
> - **Description:** Style your ticket welcome embed for active servers.
> - **Options:**  
>   - `message` (required): Welcome text
> - **Expected Behaviour:** Sets welcome text.
> - **Example:** `/tickets welcome message:"Welcome to Support"`
>
> ### /tickets colours
> - **Role:** Owner, Founder, Admin
> - **Description:** See what colours we have available for embeds.
> - **Options:** None
> - **Expected Behaviour:** Shows colour options.
> - **Example:** `/tickets colours`
>
> ### /tickets refresh
> - **Role:** Owner, Founder, Admin
> - **Description:** Re-post ticket embeds.
> - **Options:** None
> - **Expected Behaviour:** Refreshes all tickets.
> - **Example:** `/tickets refresh`
>
> ### /tickets setup
> - **Role:** Owner, Founder, Admin
> - **Description:** Assign ticket role and create ticket category and channels.
> - **Options:**  
>   - `role` (required): Discord role
> - **Expected Behaviour:** Sets up support system.
> - **Example:** `/tickets setup role:@Support`
>
> ## VALIDATION
>
> ### /updates
> - **Role:** Owner, Founder, Admin
> - **Description:** Compare your files with the latest version and get a list of updates.
> - **Options:** None
> - **Expected Behaviour:** Shows update info.
> - **Example:** `/updates`
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
> ### /base radar add
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
> - **Example:** `/base radar add x:1234 z:5678 radius:500 name:"Red Zone"`
>
> ### /base radar edit
> - **Role:** Owner, Founder, Admin
> - **Description:** Edit an existing base radar.
> - **Options:**  
>   - `id` (required): Radar ID
>   - ...other editable options
> - **Expected Behaviour:** Updates area or settings.
> - **Example:** `/base radar edit id:3 radius:999`
>
> ### /base radar delete
> - **Role:** Owner, Founder, Admin
> - **Description:** Delete a base radar.
> - **Options:**  
>   - `id` (required): Radar ID
> - **Expected Behaviour:** Removes area.
> - **Example:** `/base radar delete id:3`
>
> ### /base radar list
> - **Role:** Owner, Founder, Admin
> - **Description:** Get list of a base radars.
> - **Options:** None
> - **Expected Behaviour:** Lists all radar zones.
> - **Example:** `/base radar list`

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
> ### /base ignore add
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Add gamertag/gamertags to base radar ignore.  
>   **Must be used in radar channel.**
> - **Options:**  
>   - `gamertag` (required): Gamertag(s)
> - **Expected Behaviour:** Player(s) are ignored by radar.
> - **Example:** `/base ignore add gamertag:Player1`
>
> ### /base ignore remove
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Remove gamertag/gamertags from base radar ignore.  
>   **Must be used in radar channel.**
> - **Options:**  
>   - `gamertag` (required): Gamertag(s)
> - **Expected Behaviour:** Player(s) no longer ignored.
> - **Example:** `/base ignore remove gamertag:Player1`
>
> ### /base ignore info
> - **Role:** Owner, Founder, Admin, Base Owner
> - **Description:** Lists base radar details.  
>   **Must be used in radar channel.**
> - **Options:** None
> - **Expected Behaviour:** Shows current radar config.
> - **Example:** `/base ignore info`
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
> ### /bug
> - **Role:** `@everyone`
> - **Description:** Submit a bug report to the developers.
> - **Options:**  
>   - `description` (required): Bug details
> - **Expected Behaviour:** Sends report to devs.
> - **Example:** `/bug description:"Bug description"`
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
> ### /legion submit suggestion
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Suggestion/Request. Sends suggestion to Legion staff for review.
> - **Options:**  
>   - `message` (required): Suggestion text
> - **Expected Behaviour:** Submits suggestion to staff for review.
> - **Example:** `/legion submit suggestion message:"Add a new feature"`
>
> ### /legion submit roast
> - **Role:** `@everyone`
> - **Description:** Submit Roasts To Legion Killfeed.
> - **Options:**  
>   - `message` (required): Roast text
> - **Expected Behaviour:** Sends roast to staff for possible use as death message in embeds..
> - **Example:** `/legion submit roast message:"{USER} is slower than my grandma’s dial-up!"`
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
> ### /legion killfeed advert
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Advertisement.
> - **Options:** None
> - **Expected Behaviour:** Posts promo/invite.
> - **Example:** `/legion killfeed advert`
>
> ### /legion killfeed support
> - **Role:** `@everyone`
> - **Description:** Get a discord invite to Legion Killfeeds Support discord.
> - **Options:** None
> - **Expected Behaviour:** Posts support server invite.
> - **Example:** `/legion killfeed support`
>
> ### /subscribe
> - **Role:** `@everyone`
> - **Description:** Legion Killfeed Premium Subscription Price.
> - **Options:** None
> - **Expected Behaviour:** Shows premium pricing.
> - **Example:** `/subscribe`
>
> ### /economy help
> - **Role:** `@everyone`
> - **Description:** View the list of commands and a brief description.
> - **Options:** None
> - **Expected Behaviour:** Shows all economy commands.
> - **Example:** `/economy help`
>
> ### /economy leaderboard
> - **Role:** `@everyone`
> - **Description:** Economy leaderboard. Linked members only.
> - **Options:** None
> - **Expected Behaviour:** Shows cash rankings.
> - **Example:** `/economy leaderboard`
>