# Hi, I'm Alex Miles! 👋

I'm Alex, a Discord Bot Developer, and here is my advanced Discord Music Bot.

## **Installation | How to use the Bot**

**1.** Install the latest LTS [NodeJS](https://nodejs.org/en/).

**2.** Install the latest [Python](https://www.python.org/downloads/)

**3.** Download this repo and unzip it or use `git clone`.

**4.** Fill in everything in **`settings/config.js`**.

### _Modify - config.js_

```javascript
{
  TOKEN: "BOT_TOKEN",
  PREFIX: "BOT_PREFIX",
  mongodb : "MONGO_URL"
}
```

### _Modify - .env_

_*Rename `.env.example` to `.env.` and configure it*_

```env
TOKEN=
MONGO_URL=
PREFIX=
GUILD_ID=
```

**4.** Fill everything in the config, then type in:

```sh
npm install
```

**5.** Install additional packages:

```sh
npm install @discordjs/opus zlib-sync@latest erlpack@latest
```

**6.** Start the bot with:

```sh
node index.js
```

## Music Bot Features

- Easy-to-use Music Bot
- Supports Youtube, Spotify, Soundcloud, and 700+ other websites
- Slash commands support
- Dashboard support
- Message commands support
- Stable & up-to-date with discord.js v14
- 24/7 voice channel support
- Autoresume system
- Music request channel system
- Additional filters
- DJ system
- Works on Replit and other VPS

