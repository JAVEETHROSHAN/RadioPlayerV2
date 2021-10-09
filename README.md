# Telegram Radio Player V2
![GitHub Repo stars](https://img.shields.io/github/stars/JaveethRoshan/RadioPlayerV2?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/JaveethRoshan/RadioPlayerV2?color=green&style=flat)
![GitHub issues](https://img.shields.io/github/issues/JaveethRoshan/RadioPlayerV2)
![GitHub closed issues](https://img.shields.io/github/issues-closed/JaveethRoshan/RadioPlayerV2)
![GitHub pull requests](https://img.shields.io/github/issues-pr/JaveethRoshan/RadioPlayerV2)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/JaveethRoshan/RadioPlayerV2)
![GitHub contributors](https://img.shields.io/github/contributors/JaveethRoshan/RadioPlayerV2?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/JaveethRoshan/RadioPlayerV2?color=red)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/JaveethRoshan/RadioPlayerV2)
![GitHub](https://img.shields.io/github/license/JaveethRosham/RadioPlayerV2)
[![Bot Support](https://img.shields.io/badge/Radio%20Player%20V2-support%20group-blue)](https://t.me/TWTXBOT)


An Telegram Bot to Play Nonstop Radio/Music in Channel or Group Voice Chats.

This is also the source code of the bot which is being used for playing
Radio in [TMT X BOT](https://t.me/TWTXBOT) Channel & Music in [TMTxBoT](https://t.me/TWTXBOT) Group.

## Special Features

- Playlist, queue, 24x7 radio stream
- Loop one track when there is only one track in the playlist
- Automatically downloads audio for the first two tracks in the playlist to ensure smooth playing
- Show current playing position of the audio
- Control with buttons and commands
- Download songs from youtube as audio

## Deploy to Heroku (The Easy Way)

<p><a href="https://heroku.com/deploy?template=https://github.com/JaveethRoshan/RadioPlayerV2"> <img src="https:/https://t.me/ToonzStarsTamil/1227/the-badge&logo=heroku" width="200""/></a></p>
NOTE: Make Sure You Have Started A Voice Chat In Your Channel/Group Before Deploying!

## Heroku Vars:
1. `API_ID` : Get it from my.telegram.org
2. `API_HASH` : Get it from my.telegram.org
3. `BOT_TOKEN` : Get it from @Botfather
4. `SESSION_STRING` : Generate it from [@genStr robot](http://t.me/genStr_robot) or [![genStr](https://img.shields.io/badge/repl.it-genStr-yellowgreen)](https://repl.it/@TWTXBOT/genStr)
5. `CHAT` : ID of Channel/Group where the bot plays Music/Radio.
6. `LOG_GROUP` : Group to send Playlist, if CHAT is a Group.
7. `ADMINS` : ID of users who can use admin commands.
8. `STREAM_URL` : Stream URL of radio station to stream when the bot starts or with /radio command. Here is [Some Live Streaming Links](https://telegra.ph/Live-Radio-Stream-Links-05-17).

- Enable the worker after deploy the project to Heroku.
- Bot will starts radio automatically in given `CHAT` with given `STREAM_URL` after deploy. 
- 24x7 Music even if heroku restarts, radio stream restarts automatically.  
- To play a song just send the audio file to Bot or reply to an audio with `/play` to start playing it in the voice chat.
- To download audio you can use [@SafoneMusicBot](http://t.me/SafoneMusicBot) or `/song` command to the bot.
- Use `/help` to know about other commands & its usage.

## Requirements

- Python 3.6 or higher.
- A
  [Telegram API key](https://docs.pyrogram.org/intro/quickstart#enjoy-the-api)
  and a Telegram account.
- [FFmpeg Python](https://www.ffmpeg.org/)
- Telegram [String Session](http://t.me/genStr_robot) of the account.
- Userbot Needs To Be Admin In The Channel or Group.
- Must Start A Voice Chat In Channel/Group Before Running The Bot.

## Run On VPS (The Hard Way)

```sh
$ git clone https://github.com/JaveethRoshan/RadioPlayerV2
$ cd RadioPlayerV2
$ sudo apt-get install python3-pip ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
```
Edit **config.py** with your own values.

```sh
$ python3 main.py
```

## License
```sh
RadioPlayerV2, Telegram Voice Chat Bot
Copyright (C) 2021 TWT X BOT<https://t.me/TWTXBOT>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
```
## Credits

- [Asm Safone](https://github.com/AsmSafone) [Dev]
- [Dash Eclipse](https://github.com/dashezup) [Dev]
- [Il'ya](https://github.com/MarshalX) [For tgcalls]
- [Subin](https://github.com/subinps) [For bot support]
