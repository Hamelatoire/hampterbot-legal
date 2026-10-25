# Privacy Policy

**Hampterbot** is a Discord bot run by Hamelatoire ("I", "me"). This policy explains what the bot and its admin web app do with data. Last updated: 24 October 2026.

By adding the bot to a server or using its commands, you agree to this policy.

## What the bot reads

In servers where it is installed, the bot receives the messages sent in channels it can see. It uses message text only in the moment, to:

- delete messages that match a server's delete rules,
- award XP (levels) for messages,
- run commands that start with `!`.

**Message content is not stored.** It is not saved to a database or a file.

## What the bot stores

| Data | Why | 
|---|---|
| Your Discord user ID, the server ID, your total XP, and the time XP was last awarded to you | Levels, `/rank` and `/leaderboard` |
| Per-server settings an admin saves: music channel ID, target bot ID, XP cooldown | Moderation and levels |
| Reaction role panels an admin saves (channel ID, title, emoji and role IDs) and the ID of the message the bot posted | Reaction roles |
| The names and icons of servers the bot is in | Listing servers in the admin app |

The bot does not store usernames, avatars, message text, attachments or direct messages. It may show your username and avatar in a reply (for example on a rank card) without saving them.

If the bot leaves a server, that server's settings and XP are kept so they are still there if the bot is added again.

## Links you share with `/embed`

When you run `/embed` with a link, the bot downloads the post or video from that site, uploads it to the channel, and then deletes its temporary copy. The link is requested from the site it points to (for example Instagram, TikTok, Reddit or X), which sees a request from the bot's server.

## Other services the bot contacts

Some commands send what you typed to a third party to get an answer:

- `/weather` and `/time`: the city name, to Open-Meteo.
- `/wiki`: the topic, to Wikipedia (Wikimedia).
- `/currency`: the currency codes, to Frankfurter.

These services have their own privacy policies. The bot does not send them your Discord ID or username.

## The admin web app

Server admins can log in with Discord to manage settings. Logging in asks Discord for permission to see the list of servers you are in. A login cookie keeps you signed in. The app does not store your Discord profile; it uses your server list only to show the servers you can manage.

## Logs

The bot and the admin app write operational logs (for example errors and the links `/embed` was asked to fetch). Logs are kept on the server that runs the bot and are used only to fix problems.

## Sharing

I do not sell your data or share it with anyone, except the services listed above as needed to answer a command, and Discord itself, which runs the platform.

## Keeping and deleting data

XP and settings are kept until I remove them. To ask for the data tied to your Discord ID to be deleted, open an issue on this repository with your Discord user ID. A server admin can also ask me to remove a server's data.

## Children

Discord requires users to be at least 13 (or the minimum age in their country). The bot is not meant for anyone younger.

## Changes

If this policy changes, the new version is published here with a new date.

## Contact

Open an issue on this repository.
