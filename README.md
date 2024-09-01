# alliances

CSV file about GW2 WvW Alliances

## EU

[Online Preview](alliances-eu.csv)

You can [download the raw file](https://raw.githubusercontent.com/gw2skirmish/alliances/main/alliances-eu.csv) by right-clicking and Save link as... 

You can then open it with the Office Suite of your choice (Excel, LibreOffice, Google Sheets).

## NA

Not yet.

## Columns meaning

Column | Info
---|---
TEAM_LIVE_ID|ID of Team where Guild is currently being reported. Sources are manual, [gw2mists](https://gw2mists.com/leaderboards/player), and [gw2skirmish](https://gw2skirmish.mikamika.top/gw2claims/).
TEAM_LIVE_NAME|Name of Team according to previous ID column. Check [worlds_linked.json](https://github.com/gw2skirmish/gw2skirmish.github.io/blob/main/worlds_linked.json).
ALLIANCE_NAME|Name of the WvW Selected Guild (Alliance Leader).
ALLIANCE_LEADER|Boolean (TRUE or FALSE) if Guild is the Alliance Leader.
GUILD_NAME|Name of the Represented Guild.
GUILD_TAG|Tag of the Represented Guild.
DISCORD_URL|Link to Guild's Discord.
DISCORD_CONTACT|Contact's Discord profile.
GUILD_CONTACT|Contact's account name for in-game `/whisper` or mail.
TEAM_ORIGIN_ID|ID of Team where Guild is assigned originally by ArenaNet's API. See [eu.json](https://api.guildwars2.com/v2/wvw/guilds/eu) and [na.json](https://api.guildwars2.com/v2/wvw/guilds/na).
TEAM_ORIGIN_NAME|Name of Team according to previous ID column.
ALLIANCE_ID|Alliance Leader UUID.
GUILD_ID|Guild UUID.
MISTS_MEMBERS|Number of Guild members, as reported by gw2mists.
MISTS_LANG|Language used by Guild, as reported by gw2mists.
MISTS_URL|Guild's profile page on gw2mists.
DISCORD_POST_ALLIANCE|Direct link to message introducing the Alliance on the Alliance Discord. See invitation links for [EU](https://discord.gg/QPHHe8GZrD) and [NA](https://discord.gg/26k9WRZsua).
DISCORD_POST_RECRUITMENT|Direct link to message introducing the Guild on the Alliance Discord.
.|A personal preference to end a table.
