THC Music Bot Configs

Config vars are basically the variables which configure or modify the bot to function, which are the basic necessities of plugins or code to work. You have to set the proper mandatory vars to make it functional and start the basic features of the bot.

Get to know about all these vars in depth from our Docs. (Read Now from Here)

🔹 Mandatory Vars

These are the minimum required vars you need to set up to make THC Music Bot functional.

API_ID : Get it from my.telegram.org

API_HASH : Get it from my.telegram.org

BOT_TOKEN : Get it from @Botfather
 in Telegram

MONGO_DB_URI : Get MongoDB URI from MongoDB Atlas

LOGGER_ID : You'll need a Private Group ID for this. (Supergroup needed with id starting from -100)

OWNER_ID : Your Owner ID for managing your bot

STRING_SESSION : Pyrogram Session Needed

COOKIES : Add YouTube cookies in cookies.txt inside the cookies folder

🔹 Non-Mandatory Vars

These are extra vars for additional features inside THC Music Bot. You can leave them empty for now and add later.

DURATION_LIMIT : Max audio (music) duration for voice chat (default = 60 mins).

SONG_DOWNLOAD_DURATION_LIMIT : Duration limit for downloading songs in MP3/MP4 format (default = 180 mins).

VIDEO_STREAM_LIMIT : Max number of video calls allowed (default = 3 chats).

SERVER_PLAYLIST_LIMIT : Max playlists a user can save on the server (default = 30).

PLAYLIST_FETCH_LIMIT : Max tracks fetched from YouTube, Spotify, Apple links (default = 25).

CLEANMODE_MINS : Time after which bot deletes its old messages (default = 5 mins).

SUPPORT_CHANNEL : Channel link for your bot (if available).

SUPPORT_GROUP : Group support link for your bot (if available).

🔹 Play FileSize Limit Vars

Maximum file size limit for audio and video that users can play from your bot. (Only Bytes Size Accepted)
👉 Convert MB to bytes here: GBMB Converter

TG_AUDIO_FILESIZE_LIMIT : Max audio file size (default = 104857600 bytes = 100MB).

TG_VIDEO_FILESIZE_LIMIT : Max video file size (default = 1073741824 bytes = 1GB).

🔹 Bot Vars

Vars for configuring bot behavior.

PRIVATE_BOT_MODE : True = private use only, False = all groups (default = False).

YOUTUBE_EDIT_SLEEP : Sleep duration for YouTube downloader (default = 3 sec).

TELEGRAM_EDIT_SLEEP : Sleep duration for Telegram downloader (default = 5 sec).

AUTO_LEAVING_ASSISTANT : True = assistant leaves after set time.

ASSISTANT_LEAVE_TIME : Time after which assistant leaves served chats (default = 5400 sec = 90 mins).

AUTO_DOWNLOADS_CLEAR : True = delete downloads after playback ends.

AUTO_SUGGESTION_MODE : True = bot suggests commands randomly in chats.

AUTO_SUGGESTION_TIME : Time after which bot suggests commands (default = 5400 sec = 90 mins).

SET_CMDS : True = bot sets commands automatically in menu.

🔹 Spotify Vars

For Spotify playback support.

SPOTIFY_CLIENT_ID : Get it from Spotify Developer Dashboard

SPOTIFY_CLIENT_SECRET : Get it from Spotify Developer Dashboard

(Optional, leave empty if you don’t need Spotify features.)

🔹 Heroku Vars

For Heroku-compatible modules like get_log, usage, update, etc.

HEROKU_API_KEY : Get from Heroku Account Settings

HEROKU_APP_NAME : Your Heroku app name for THC Music Bot

🔹 Custom Repo Vars

For using your own customized or forked repo.

UPSTREAM_REPO : Your upstream repo URL or forked repo.

UPSTREAM_BRANCH : Default branch name of your repo.

GIT_TOKEN : Your GitHub token (only if repo is private).

GITHUB_REPO : Your GitHub repo URL (will show on /start command).

🔹 Images/Thumbnail Vars

You can customize images used in THC Music Bot.
👉 Generate Telegraph links from @syn_ixbot

START_IMG_URL : Image shown on /start.

PING_IMG_URL : Image for /ping.

PLAYLIST_IMG_URL : Image for /play.

GLOBAL_IMG_URL : Image for /stats.

STATS_IMG_URL : Image for /stats.

TELEGRAM_AUDIO_URL : Image when audio is played from Telegram.

TELEGRAM_VIDEO_URL : Image when video is played from Telegram.

STREAM_IMG_URL : Image when m3u8/index links are played.

SOUNCLOUD_IMG_URL : Image for SoundCloud playback.

YOUTUBE_IMG_URL : Image when thumbnail generation fails.

SPOTIFY_ARTIST_IMG_URL : Image for Spotify artist in inline mode.

SPOTIFY_ALBUM_IMG_URL : Image for Spotify album in inline mode.

SPOTIFY_PLAYLIST_IMG_URL : Image for Spotify playlist in inline mode.

🔹 Multi Assistant Mode

You can use up to 5 Assistant Clients (allowing the bot to work in 2000–2500 chats simultaneously).

STRING_SESSION2 : Pyrogram Session

STRING_SESSION3 : Pyrogram Session

STRING_SESSION4 : Pyrogram Session

STRING_SESSION5 : Pyrogram Session

