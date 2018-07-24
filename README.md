# FortniteChecker-Docs
A Fortnite Bot that provides you with images for stats alongside other features.

Repo is a full user guide on how to use the bot.

[![Discord Bots](https://discordbots.org/api/widget/438672538831290369.svg)](https://discordbots.org/bot/438672538831290369)

## Getting Started

To add FortniteChecker to your own Discord server, click [here](https://discordapp.com/oauth2/authorize?client_id=438672538831290369&scope=bot&permissions=8)

The bot needs certain permissions to carry out the commands available. If it doesnt have the following permissions the bot may not work correctly. Majority of problems I get is from people not giving the bot its needed permissions e.g `SEND MESSAGES`, bot cant respond without this permission.

FortniteChecker Needed Permissions:

`MANAGE ROLES` - Only necessary for the premium bot <br />
`MANAGE CHANNELS` - Needed for Dynamic Channels <br />
`KICK MEMBERS` - Needed to use the kick command <br />
`BAN MEMBERS` - Needed to use the ban command <br />
`MANAGE NICKNAMES` - Only necessary for the premium bot <br />
`READ TEXT & SEE VOICE` - Needed so it can respond to commands <br />
`SEND MESSAGES` - Needed to provide a response for commands <br />
`MANAGE MESSAGES` - Needed for clear command and other small commands <br />
`ATTACH FILES` - Needed for returning fortnite stats <br />
`READ MESSAGE HISTORY` - Needed to read messages and respond <br />
`ADD REACTIONS` - Needed for the poll command

If you don't want to have any hassle with Permissions just give it `ADMINISTRATOR`

If you do require any assistance with setup or have a problem with the bot please join the support server [here](https://discord.gg/CjyGwrJ) or message me on discord here 𝕮𝖗𝖎𝖕𝖕𝖑𝖊#1870.

## How To Use

Using the command .help will provide you with a list of all available commands.

## General Commands

General commands are just basic commands that you can use for retreiving info or making sure the bot is online and responsive.

```
.hi - The bot will respond with hello, used to test if bot is online
.suggest - This will provide you with a link where you can suggest ideas for bot commands
.report - This will provide you with a link where you can report bugs with the bot
.ping - This will provide you with the average latency
.poll <Question> - This will make a basic poll in the channel you call the command in
.botinfo - This will provide you with some basic info on the bot
.serverinfo - This will provide you with some basic info on the server
.invite - This will provide you with a invite link for the bot
.say <Text> - This will make the bot repeat the message after the command
.translate <Sentence> - This will translate a sentence with auto detect to English
.translateto <From> <To> <Sentence> - This will translate a sentence from a selected language to another selected language, For the param From and To you have to use ISO codes. There will be a list of them under this block.
.languages - This will provide you with all the possible ISO codes for the supported languages
```

## ISO codes for translateto command

| A-G        | H-O           | P-Z  |
| ------------- |:-------------:| -----:|
| `af` - Afrikaans      | `ht` - Haitian Creole | `ps` - Pashto |
| `sq` - Albanian      | `ha` - Hausa      |   `fa` - Persian |
| `am` - Amharic | `iw` - Hebrew      |    `pl` - Polish |
| `ar` - Arabic      | `hi` - Hindi | `pt` - Portuguese |
| `hy` - Armenian      | `hu` - Hungarian      |   `ma` - Punjabi |
| `az` - Azerbaijani | `is` - Icelandic      |    `ro` - Romanian |
| `eu` - Basque      | `ig` - Igbo | `ru` - Russian |
| `be` - Belarusian      | `id` - Indonesian      |   `sm` - Samoan |
| `bn` - Bengali | `ga` - Irish      |    `gd` - Scots Gaelic |
| `bs` - Bosnian      | `it` - Italian | `sr` - Serbian |
| `bg` - Bulgarian      | `ja` - Japanese      |   `st` - Sesotho |
| `ca` - Catalan | `jw` - Javanese      |    `sn` - Shona |
| `ny` - Chichewa      | `kn` - Kannada | `sd` - Sindhi |
| `co` - Corsican      | `kk` - Kazakh      |   `si` - Sinhala |
| `hr` -  Croatian | `km` - Khmer      |    `sk` - Slovak |
| `cs` - Czech      | `ko` - Korean | `sl` - Slovenian |
| `da` - Danish      | `ku` - Kurdish      |   `so` - Somali |
| `nl` - Dutch | `ky` - Kyrgyz      |    `es` - Spanish |
| `en` - English      | `lo` - Lao | `su` - Sundanese |
| `eo` - Esperanto      | `la` - Latin      |   `sw` - Swahili |
| `et` - Estonian | `lv` - Latvian      |    `sv` - Swedish |
| `tl` - Filipino      | `lt` - Lithuanian      |   `tg` - Tajik |
| `fi` - Finnish | `lb` - Luxembourgish      |    `ta` - Tamil |
| `fr` - French      | `mk` - Macedonian      |   `te` - Telugu |
| `fy` - Frisian | `mg` - Malagasy      |    `th` - Thai |
| `gl` - Galician      | `ms` - Malay      |   `tr` - Turkish |
| `ka` - Georgian | `ml` - Malayalam      |    `uk` - Ukrainian |
| `de` -  German      | `mt` - Maltese      |   `ur` - Urdu |
| `el` - Greek | `mi` - Maori      |    `uz` - Uzbek |
| `gu` - Gujarati      | `mr` -  Marathi      |   `vi` - Vietnamese |
|  | `mn` - Mongolian      |    `cy` - Welsh |
|  | `my` - Myanmar      |   `xh` - Xhosa |
|  | `ne` - Nepali      |    `yi` - Yiddish |
|  | `no` - Norwegian      |    `yo` - Yoruba |
|  |       |    `zu` - Zulu |

## Fortnite Commands

This is a list of all the available Fortnite related commands.

```
.lf1 - This sends a message that you are looking for one more player
.status - This lets you know if the fortnite servers are up or down
```
### Link Fortnite Account

```
.link <Platform> <Ign> - This will link your fortnite account to your discord account
.unlink - This will unlink your fortnite account from your discord account
```

After you have linked your account with the command above you are simply able to do any of the stats commands without having to enter platform or ign. You are able to do `.fstats` `.fseason4` `.fseason5` `.flast7` and it will return the stats for the account that you have linked.

### Fortnite Stats

```
.fstats <Platform> <Ign> - Look up your overall stats for fortnite, provides an image
.fseason4 <Platform> <Ign> - Look up your season 4 stats for fortnite, provides an image
.fseason5 <Platform> <Ign> - Look up your season 5 stats for fortnite, provides an image
.flast7 <Platform> <Ign> - Look up your last 7 days stats for fortnite, provides an embed
```

The above are all the available Fortnite Stats commands. The supported platforms are: pc | psn | xbl. You  are able to check your Overall Stats, Seasonal Stats and Weekly Stats.

### Fortnite Weapons

```
.weapon <ID> - Display stats of a particular weapon
.weaponlist - Display all available weapons supported
```

Search the statistics of any weapon in fortnite and contrast and compare. Learn whats best for each situation.

### Weapon ID Table

| ID        | Weapon Name    |
| ------------- | -----:|
| famas     | Famas Assault Rifle |
| burst     | Burst Assault Rifle |
| m4      | M4 Assault Rifle |
| scar     | SCAR Assault Rifle |
| scoped      | Scoped Assault Rifle |
| tommy     | Drum Gun  |
| lmg      | Light Machine Gun |
| minigun      | Minigun |
| thermal      | Thermal Scoped Assault Rifle |
| heavy     | Heavy Shotgun |
| pump      | Pump Shotgun |
| tac      | Tactical Shotgun |
| dual      | Dual Pistol |
| deagle      | Hand Cannon |
| pistol      | Pistol |
| revolver      | Revolver |
| usp      | Suppressed Pistol |
| smg      | Suppressed Submachine Gun |
| newsmg     | Submachine Gun |
| bolt      | Bolt-Action Sniper Rifle |
| hunting      | Hunting Rifle |
| semi      | Semi-Auto Sniper Rifle |
| launcher      | Grenade Launcher |
| rocket      | Rocket Launcher |

## Fun Commands

```
.8ball <Question> - Ask the Magic 8-Ball a question of your choice
.dog - This provides you with a random picture of a dog
.cf <Side> - Try your luck with a coinflip or settle a debate with it
.hug - Bot gives you a hug to cheer you up
.yomomma - Get a randomly selected yo momma joke for your own entertainment
```

These commands are for when you have nothing better to be doing. More games are to be implemented in the future.

## Moderation Commands

```
.clear <Amount> - Deletes the specified number of messages in the channel
.kick <@user> <Reason> - Kick a member from the server with a reason for what he did
.ban <@user> <Reason> - Ban a member from the server with a reason for what he did
```

Keep track and log who you punish on your private discord server.

## Dynamic Channels Commands

```
.setdynamic <createChannelID> <createCategoryID> - Set the create channel room and category for dynamic channels on your server
.resetdynamic - Clear the data for dynamic channels for the server
```

Dynamic Channels are channels that are automatically created as they are needed. This allows for your server to look cleaner and not have to be cluttered with voice channels. The bot needs the perms listed above in order for this feature to function correctly.

## Premium Feature

In order to gain premium on the bot you must pay £10 as a once off payment. Extra features such as custom commands for your server will vary in cost depending on what you want but we can sort something out.

### What do I get with premium?

There is a custom ranking system for fortnite implemented into the bot for premium users. You are able to rank the players in your discord by Wins or K/d, all depends on your preference.

Your also able to setup custom roles so users can give themselves the role rather than you having to hand out certain roles.

Alongside premium you can also suggest extra custom commands.

## Credits

FortniteChecker is being developed and maintained by 𝕮𝖗𝖎𝖕𝖕𝖑𝖊#1870 using Discord.js. The stats are provided by FortniteTracker.com
