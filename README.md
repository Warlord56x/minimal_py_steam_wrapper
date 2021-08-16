# minimal_py_steam_wrapper

## A minimal steam wrapper made in python

### Why was it made?

- This little file was created when someone said that they wanted their discord bot (that was created in [Discord.py](https://github.com/Rapptz/discord.py)) to recommend games to them either periodically or with some command calls.

- Then what happend was that there isn't a specific steam wrapper,
  for this kind of work. It was either complex or not compatible etc...

That covers the "Why was it made?" section.

How does it work?

- Basically it uses [requests](https://github.com/psf/requests) to do some GET requests on the "http://api.steampowered.com" api.

- Stores the appids in a json file to avoid making unnecessarily calls on the api.

- Using the appids from the file, it can constructs a url from the given appid (It's pretty simple).

- There is a random recommend function, using random and the games.json file.

# Links

- [Requests](https://github.com/psf/requests)
- [Discord.py](https://github.com/Rapptz/discord.py)
- [The bot using this method](https://github.com/holorum/USSLongIslandBot)
