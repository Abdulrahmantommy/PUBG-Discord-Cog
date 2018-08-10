# PUBG-Discord-Bot

# How to use:
- Put the cog in the [Basic Cog Bot](https://github.com/stroupbslayen/Basic-Cog-Bot) cog folder.

- Use Pip to install BeautifulSoup: `pip install bs4`

- Edit default values in pubg.py if you want. Current Default: `mode='squad-fpp', region='na'`

- If everything goes well, it will connect and you can call it using `pubgstats {playername}` with any valid filters.

![example](https://i.imgur.com/GutJn6j.png)

# What's new:
- Rebuilt for discord.py rewrite

- Seasons are automatically updated

- Tiers and tier badges are output
- Now only a single cog
- Made to just drop into the [Basic Cog Bot](https://github.com/stroupbslayen/Basic-Cog-Bot)
- Users can register their in game names with `pubg_register {in-game-name}` this will register them to the servers 'team' and they can look themselves up without entering their name in the `pubgstats` command. Stats are also retrieved faster.

![registered](https://i.imgur.com/6HEVhVm.png)

- Team member stats can be group retrieved with `pubgstats team`

![team](https://i.imgur.com/Npko2zk.png)

- New command: `pubgleaderboard` will show you how people on your team stack up against eachother. Leaderboards are sorted by average damage/round.

![leaderboard](https://i.imgur.com/ocTJW6m.png)

# Features:
- Can do multiple players at one time.
- Can change search criteria using the valid filters:

  `modes = ['solo','duo','squad','solo-fpp','duo-fpp','squad-fpp']`

  `regions = ['as', 'sea', 'na', 'eu', 'krjp','sa','oc']`

- Should correct most errors and at least output something.

# Issues:
- If your name is one of the game modes, *team*, or regions this won't work for you.
