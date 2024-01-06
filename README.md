# RE-LEECH-BOT


---
-  Clone this repo:
```
git clone https://github.com/Sridhark01/RE_LEECH_PRO RE_LEECH_PRO/ && cd RE_LEECH_PRO
```
 
- Switch to deploy branch:
```
git checkout dep
```

- Login to heroku:
```
heroku login
```

- Create heroku app:
```
heroku create --region us YOUR-APP-NAME
```

- Add remote: ```heroku git:remote -a YOUR-APP-NAME```

- Create container: ```heroku stack:set container```

- Push to heroku: ```git push heroku dep:master -f```


### Extras

- To delete the app: ```heroku apps:destroy YOUR-APP-NAME```

- To restart dyno: ```heroku restart```

- To turn off dyno: ```heroku ps:scale web=0```

- To turn on dyno: ```heroku ps:scale web=1```

- To set heroku variable: ```heroku config:set VARNAME=CONFIG_FILE_URL```

- To get live logs: ```heroku logs -t```
    
------

### 🤖 ***Bot Commands***

<details>
  <summary>Bot commands can be automatically set by <code>SET_COMMANDS</code> Var <sup><kbd>View All Commands</kbd></sup></summary>

```
mirror - or /m Mirror
qbmirror - or /qm Mirror torrent using qBittorrent
leech - or /l Leech
qbleech - or /ql Leech torrent using qBittorrent
clone - Copy file/folder to Drive
count - Count file/folder from Drive
ytdl - or /y Mirror yt-dlp supported link
ytdlleech - or /yl Leech through yt-dlp supported link
usetting - User settings
bsetting - Bot settings
status - Get Mirror Status message
btsel - Select files from torrent
rss - Rss menu
list - Search files in Drive
search - Search for torrents with API
cancel - Cancel a task
cancelall - Cancel all tasks
del - Delete file/folder from Drive
log - Get the Bot Log
shell - Run commands in Shell
restart - Restart the Bot
stats - Bot Usage Stats
ping - Ping the Bot
help - All cmds with description
```

</details>



    
-----

## 🏅 **Bot Authors**
<details>
    <summary><b>Click Here For Description</b></summary>

|<img width="80" src="https://avatars.githubusercontent.com/u/105407900">|<img width="80" src="https://avatars.githubusercontent.com/u/113664541">|<img width="80" src="https://avatars.githubusercontent.com/u/84721324">|
|:---:|:---:|:---:|
|[`Sridhar`](https://github.com/sridhark01)|[`SilentDemonSD`](https://github.com/SilentDemonSD)|[`CodeWithWeeb`](https://github.com/weebzone)|[`Maverick`](https://github.com/MajnuRangeela)|
|Author and DDL, UI Design, More Customs..|Author and Wraps Up Features|Co-Author & Bug Tester|

</details>

