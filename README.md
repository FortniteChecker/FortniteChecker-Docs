# FortniteChecker-Docs
A Fortnite Bot that provides you with images for stats alongside other features.

Repo is a full user guide on how to use the bot.

[![Discord Bots](https://discordbots.org/api/widget/438672538831290369.svg)](https://discordbots.org/bot/438672538831290369)

## Getting Started

To add FortniteChecker to your own Discord server, click [here](https://discordapp.com/oauth2/authorize?client_id=438672538831290369&scope=bot&permissions=8)

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

## How To Use

Using the command .help will provide you with a list of all available commands.

## General Commands

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

```
.lf1 - This sends a message that you are looking for one more player
.status - This lets you know if the fortnite servers are up or down
.fstats <Platform> <Ign> - Look up your overall stats for fortnite, provides an image
.fseason4 <Platform> <Ign> - Look up your season 4 stats for fortnite, provides an image
.fseason5 <Platform> <Ign> - Look up your season 5 stats for fortnite, provides an image
.flast7 <Platform> <Ign> - Look up your last 7 days stats for fortnite, provides an embed
.weapon <Name> - Display stats of a particular weapon
.weaponlist - Display all available weapons supported
```

## Fun Commands

```
.8ball <Question> - Ask the Magic 8-Ball a question of your choice
.dog - This provides you with a random picture of a dog
.cf <Side> - Try your luck with a coinflip or settle a debate with it
.hug - Bot gives you a hug to cheer you up
.yomomma - Get a randomly selected yo momma joke for your own entertainment
```

## Moderation Commands

```
.clear <Amount> - Deletes the specified number of messages in the channel
.kick <@user> <Reason> - Kick a member from the server with a reason for what he did
.ban <@user> <Reason> - Ban a member from the server with a reason for what he did
```

## Dynamic Channels Commands

```
.setdynamic <createChannelID> <createCategoryID> - Set the create channel room and category for dynamic channels on your server
.resetdynamic - Clear the data for dynamic channels for the server
```

Dynamic Channels are channels that are automatically created as they are needed. This allows for your server to look cleaner and not have to be cluttered with voice channels. The bot needs the perms listed above in order for this feature to function correctly.

## Premium Feature

In order to gain premium on the bot you must pay £10 as a once off payment. Extra features such as custom commands for your server will vary in cost depending on what you want but we can sort something out.
