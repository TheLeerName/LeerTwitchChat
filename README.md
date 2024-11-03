# Leer's Twitch Chat
Twitch chat for displaying on browser source in OBS

## Displays
- 7TV channel and global emotes
- Twitch channel and global emotes
- Twitch channel and global badges

## How to use?
1. Paste this link in OBS browser source
```
https://theleername.github.io/LeerTwitchChat?login=<twitch_channel_name>&clientID=<twitch_bot_client_id>&token=<twitch_bot_access_token>&size=<fontSize>&decay=<decay>&decayDuration=<decayDuration>
```
2. Replace placeholders with some parameters in link:
| Parameter | Description | Example | Required |
|---|---|---|---|
| <twitch_channel_name> | Twitch channel name | xqc | Yes |
| <twitch_bot_client_id> | Client ID of your twitch bot | bp6vo2242t6s58epgeck17dabsabu1 (fake) | No (if didnt specified, emotes and badges will be not displayed) |
| <twitch_bot_access_token> | Access token of your twitch bot | sfjhjtvr06al24jp4vnbj8km3njc91 (fake) | No (if didnt specified, emotes and badges will be not displayed) |
| <fontSize> | (float) Font size of messages in chat | 16 | No (default value: `16`) |
| <decay> | (seconds) Specifies how much time message will be seen before disappearing, if `0`, message will stay before going outside screen | 5 | No (default value: `0`) |
| <decayDuration> | (seconds) Specifies how long the disappearing will last | 0.5 |  |
3. If you don't want change some not required parameters, just remove them
for example `https://theleername.github.io/LeerTwitchChat?login=<twitch_channel_name>&size=20` will be after removing `https://theleername.github.io/LeerTwitchChat?login=<twitch_channel_name>`
4. Now you have the cooliest chat :3