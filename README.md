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

## FAQ

### Why should I use this instead of gw2mists?

Every guild that joins WvW will get assigned a team by ArenaNet,
If you joined an alliance, then you will join the team of that **selected** guild,
and the guild you **represent** will also get a team assigned, which might be a different one.

### But people just need to fix their gw2mists profile/alliance override

And that's where the data gets really messy, because some will, others won't.
There are many players that did not register to gw2mists.

### What about gw2skirmish/claims?

Claims are limited in number, 
and a solo roamer can claim on any team and gather points,
while the main squad will just fight and avoid claiming.

### But it's ugly

Yeah. It also contains a lot of manual inputs subject to human error (Excel auto-correct...)
With people avoiding gw2mists, claims, and ArenaNet's api giving basic info,
with alliances changing every now and then, without updating status on discord or gw2mists,
it's really hard to keep up with news.
But with a mix of manual work and automation to check the validity of data, 
I can try to have it displayed nicely in the future.
