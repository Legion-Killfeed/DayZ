# [Legion Killfeed's Slash Commands](https://killfeed.co/commands)

## Owner Commands
| Command | Description |
|---------|-------------|
| `/reset stats player` | Wipe a player's stats. **[WARNING: This can't be undone!]** |
| `/reset stats server` | Wipe a server's stats. **[WARNING: This can't be undone!]** |

## Setup Commands			## Additional Settings
| Command | Description |			| Command | Description |
|---------|-------------|			|---------|-------------|
| `/setup token` | Add Server(s) using a Nitrado Token (TOKEN USER ONLY) |			| `/settings channels assign` | Assign feed to channel (Admin+) |
| `/setup channels` | Automated setup (channel creation + perms) for killfeed activation (TOKEN USER ONLY) |			| `/settings channels create` | Add a channel from the list of channels for your selected server (Admin+) |
| `/setup activate` | Restart killfeed process if switched off (TOKEN USER ONLY) |			| `/settings flag_logs` | Flag build logs to a separate channel (Admin) |
| `/set discord` | Assign Discord server (TOKEN USER ONLY) |			| `/legion autostart` | Auto-restart server if stopped for 10 minutes |

## Additional Settings
| Command | Description |
|---------|-------------|
| `/settings channels assign` | Assign feed to channel (Admin+) |
| `/settings channels create` | Add a channel from the list of channels for your selected server (Admin+) |
| `/settings flag_logs` | Flag build logs to a separate channel (Admin) |
| `/legion autostart` | Auto-restart server if stopped for 10 minutes |

## Admin Commands
| Command | Description |
|---------|-------------|
| `/admin tracker` | Track command usage |

### Killfeed Settings (Admin)
| Command | Description |
|---------|-------------|
| `/settings view` | View your server's settings in Legion's database |
| `/settings admin roles` | Assign killfeed permissions to a Discord role |
| `/settings linked role` | Role assigned to members upon account linking |
| `/settings feeds clean` | Enable/Disable message purging for Status, Heatmaps, Leaderboards |
| `/settings economy` | All economy settings except bounties |
| `/settings bounty` | Assign default bounty amount (required for bounty channel) |
| `/settings plon` | Enable/Disable `/plon` command |
| `/settings set_plon_prefix` | Change prefix for online voice channel count |
| `/logs autofeed` | Assign Auto Download Logs Channel |

### Styling
| Command | Description |
|---------|-------------|
| `/legion colours view` | View available embed colors |
| `/legion colours assign` | Assign embed color for unspecified embeds |
| `/settings add logo` | Add/remove a logo via URL for a selected server |
| `/settings locations` | Location settings for multiple feeds (Admin) |

### Rename Options (Admin)
| Command | Description |
|---------|-------------|
| `/settings rename` | Change server's name in killfeed |
| `/server details edit` | Change server name/description |
| `/server details view` | View server details |

### Scheduler (Only Damage Working)
| Command | Description |
|---------|-------------|
| `/schedule server restarts` | Schedule automated server restarts (WIP) |
| `/schedule damage cancel` | Cancel base damage scheduler (Admin) |
| `/schedule damage enabled` | Set schedule for enabling base damage (Admin) |
| `/schedule damage disabled` | Set schedule for disabling base damage (Admin) |

### Full Map Auto Ban
| Command | Description |
|---------|-------------|
| `/settings mode autoban` | Autoban on Kill/Death/No Autoban (Admin) |
| `/settings mode ignore` | Exempt specific gamertags from autoban (Moderator) |

### Trader/Shoppi (Trader + Moderator + Admin + Founder + Owner) (BUGGED RIGHT NOW)
| Command | Description |
|---------|-------------|
| `/shoppi admin location` | Set trader location for item spawn or allow anywhere |
| `/shoppi admin status` | View Shoppi status, pending orders, etc. |
| `/shoppi config start` | Sends config files for trader setup |
| `/shoppi config setup` | Setup config (requires file) and assign trader channels |
| `/shoppi config colour` | Set embed color for Shoppi |
| `/shoppi config restarts` | Set restart intervals and bot behavior |

### Base Radar
| Command | Description |
|---------|-------------|
| `/base radar add` | Create a base radar for your selected server |
| `/base radar edit` | Edit a base radar for your selected server |
| `/base radar delete` | Delete a base radar from your selected server |
| `/base radar list` | List base radars for your selected server |

### Heatmaps
| Command | Description |
|---------|-------------|
| `/heatmap Kills` | PVP kills heatmap |
| `/heatmap Damage` | PVP damage heatmap |
| `/heatmap Locations` | Heatmap of player locations |
| `/heatmap Pinmap` | Pinpoint map of player locations |
| `/heatmap Nitrado Usage` | CPU/RAM usage heatmap |

### Gatekeeper (+ Owner + Founder)
| Command | Description |
|---------|-------------|
| `/add info_whitelist` | No description provided |
| `/add upload_whitelist` | Upload file to add gamertags to whitelist |
| `/remove rebuild_whitelist` | Rebuild Whitelist |
| `/add ban` | Ban gamertag(s) |
| `/remove ban` | Unban gamertag(s) |
| `/view bans` | View ban list |
| `/add whitelist` | Whitelist gamertag(s) |
| `/remove whitelist` | Unwhitelist gamertag(s) |
| `/view whitelist` | View whitelist |
| `/add priority` | Prioritize gamertag(s) |
| `/remove priority` | Remove priority status from gamertag(s) |
| `/view priority` | View priority list |

### General (No Perms Needed)
| Command | Description |
|---------|-------------|
| `/subscribe` | Legion Killfeed Premium Subscription Price |
| `/help` | View help categories |
| `/info` | Get bot information |
| `/killfeed advert` | Legion Killfeed advertisement |
| `/killfeed support` | Get Discord invite to Legion Killfeed support |
| `/bug` | Submit a bug report |
| `/fight` | Challenge a user to a fight (loser gets timed out) |
| `/godmode` | Fake "God Mode" command |
| `/plon` | View online players (slow for accuracy) |
| `/locate` | DM last logged location to linked player |
| `/last restart` | Get last restart, next restart, and player count |

![Legion Killfeed Banner](https://killfeed.co/a/img/lkb.webp) ![Legion Killfeed Logo](https://killfeed.co/a/img/logo.gif)
