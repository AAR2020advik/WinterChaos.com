# Wiki-Bot[<img src="https://translate.wikibot.de/widgets/wiki-bot/-/svg-badge.svg" alt="Translation status" align="right" />](#translations)[<img src="https://github.com/Markus-Rost/discord-wiki-bot/workflows/Node.js CI/badge.svg" alt="Node.js CI" align="right" />](https://github.com/Markus-Rost/discord-wiki-bot/actions)
[<img src="/dashboard/src/icon.png" alt="Wiki-Bot" align="right" width="200" />](https://discord.com/oauth2/authorize?client_id=461189216198590464&permissions=939904064&scope=bot+applications.commands)

**Wiki-Bot** is a bot for [Discord](https://discord.com/) with the purpose to easily link and search [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) sites like [Wikipedia](https://www.wikipedia.org/) and [Fandom](https://www.fandom.com/) wikis. **Wiki-Bot** shows short descriptions and additional info about pages and is able to resolve redirects and follow interwiki links.

**Wiki-Bot** has translations for Bengali, German, English, Spanish, French, Hindi, Korean, Polish, Brazilian Portuguese, Russian, Swedish, Turkish, Simplified Chinese and Traditional Chinese.

[Use this link to invite **Wiki-Bot** to your Discord server.](https://discord.com/oauth2/authorize?client_id=461189216198590464&permissions=939904064&scope=bot+applications.commands)

[Change the server settings for **Wiki-Bot** using the dashboard.](https://settings.wikibot.de/)

Support server: [https://discord.gg/v77RTk5](https://discord.gg/v77RTk5)

#### Table of Contents
* [Setup](#setup)
* [Commands](#commands)
  * [Admin](#admin)
* [User Verification](#user-verification)
* [Recent Changes Webhook](#recent-changes-webhook)

## Setup
After [inviting](https://discord.com/oauth2/authorize?client_id=461189216198590464&permissions=939904064&scope=bot+applications.commands) **Wiki-Bot** to your server you need to set the wiki you want to search by default. You do this with the `!wiki settings` command or by using the [dashboard](https://settings.wikibot.de/).
* Change the wiki with `!wiki settings wiki <url>`
  * Example: `!wiki settings wiki https://minecraft.fandom.com/wiki/Minecraft_Wiki`
* Change the language with `!wiki settings lang <language>`
  * Example: `!wiki settings lang German`
