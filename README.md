<p align="center">
  <img src=IMG_20211219_161930_849.jpg  alt="Movie World Logo">
</p>
<h1 align="center">
  <b>Movie World</b>
</h1>


[![Stars](https://img.shields.io/github/stars/LordSA/movie-world?style=flat-square&color=yellow)](https://github.com/LordSA/movie-world/stargazers)
[![Forks](https://img.shields.io/github/forks/LordSA/movie-world?style=flat-square&color=orange)](https://github.com/LordSA/movie-world/fork)
[![Size](https://img.shields.io/github/repo-size/LordSA/movie-world?style=flat-square&color=green)](https://github.com/LordSA/movie-world/)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/LordSA/movie-world)   
[![Contributors](https://img.shields.io/github/contributors/LordSA/movie-world?style=flat-square&color=green)](https://github.com/LordSA/movie-world/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/LordSA/movie-world/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/LordSA/movie-world.svg)](https://stars.medv.io/LordSA/movie-world)


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature

## Variables

Read [this](https://telegram.dog/mwpro11/12) before you start messing up with your edits.

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more


## Deploy
You can deploy this bot anywhere.

<i>**[Watch Deploying Tutorial...](https://youtu.be/1G1XwEOnxxo)**</i>

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://telegram.dog/XTZ_HerokuBot?start=TG9yZFNBL21vdmllLXdvcmxkIG1haW4">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/LordSA/movie-world.git
# Install Packages
pip3 install U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>

<details><summary>Deploy To Railway</summary>
<p>
<br>
<a href="https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Flordsadevil%2Fmovie-world&envs=API_HASH%2CAPI_ID%2CBOT_TOKEN%2CCHANNELS%2CADMINS%2CAUTH_CHANNEL%2CDATABASE_URI%2CDATABASE_NAME">
  <img src="https://railway.app/button.svg" alt="Deploy">
</a>
</p>
</details>


## Commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /connections - view the connections
* /settings - settings for connected groups
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://telegram.dog/EvaMariaSupport)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/mwpro11)

## Credits 
* [![MovieWorld-Devs](https://img.shields.io/static/v1?label=MovieWorld&message=devs&color=critical)](https://telegram.dog/MovieWorldDevs)


## Thanks to 
 - Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
 - Thanks To Mahesh For His Awesome [Media-Search-bot](https://github.com/Mahesh0253/Media-Search-bot)
 - Thanks To [Trojanz](https://github.com/trojanzhex) for Their Awesome [Unlimited Filter Bot](https://github.com/TroJanzHEX/Unlimited-Filter-Bot) And [AutoFilterBoT](https://github.com/trojanzhex/auto-filter-bot)
 - Thanks To All Everyone In This Journey

### Note

[Note To A So Called Dev](https://telegram.dog/subin_works/203): 

Kanging this codes and and editing a few lines and releasing a V.x  or an [alpha](https://telegram.dog/subin_works/204), beta , gama branches of your repo wont make you a Developer.
Fork the repo and edit as per your needs.

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/EvamariaTG/evamaria/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

## Inspiration
This is an attempt to create a clone of a BOAT made out of [banana trees 🌳](https://telegram.dog/GetTGLink/4187)

[![For Vaza](https://telegra.ph/file/e743b0c8a04252774bac2.jpg)](https://telegra.ph/file/98342dc186fd7484cba91.mp4 "Oru Kootam Vazhakalk samarpikkunnu")
