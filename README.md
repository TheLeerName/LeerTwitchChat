# Leer's Stream Chat
Stream chat for displaying on browser source in OBS

## Twitch messages displays
- 7TV channel and global emotes
- Twitch channel and global emotes
- Twitch channel and global badges

## How to use?
1. Paste this link in OBS browser source
```
https://theleername.github.io/LeerStreamChat?twitch_login=<twitch_channel_name>&twitch_client_id=<twitch_bot_client_id>&twitch_token=<twitch_bot_access_token>&lang=<cur_lang>&size=<font_size>&indent=<indent_size>&remove_msg=<remove_msg>&decay=<decay_msg>&decay_duration=<decay_msg_duration>
```
2. Replace placeholders with some parameters in link:

| Parameter                   | Description                                                                                                                       | Example                                 | Required                                                         |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------|------------------------------------------------------------------|
| `<twitch_channel_name>`     | Twitch channel name                                                                                                               | `xqc`                                   | Yes                                                              |
| `<twitch_bot_client_id>`    | Client ID of your twitch bot                                                                                                      | `bp6vo2242t6s58epgeck17dabsabu1` (fake) | No (if didnt specified, emotes and badges will be not displayed) |
| `<twitch_bot_access_token>` | Access token of your twitch bot                                                                                                   | `sfjhjtvr06al24jp4vnbj8km3njc91` (fake) | No (if didnt specified, emotes and badges will be not displayed) |
| `<cur_lang>`                | Which language chat will use to print messages, for now only exists `en` and `ru`                                                 | `en`                                    | No (default value: `en`)                                         |
| `<font_size>`               | (float) Font size of messages in chat                                                                                             | `16`                                    | No (default value: `16`)                                         |
| `<indent_size>`             | Indent of messages                                                                                                                | `4`                                     | No (default value: `4`)                                          |
| `<remove_msg>`              | If `1`, then message will be removed when it was removed by moderator in actual chat                                              | `1`                                     | No (default value: `1`)                                          |
| `<decay_msg>`               | (seconds) Specifies how much time message will be seen before disappearing, if `0`, message will stay before going outside screen | `5`                                     | No (default value: `0`)                                          |
| `<decay_msg_duration>`      | (seconds) Specifies how long the disappearing will last                                                                           | `0.5`                                   | No (default value: `0.5`)                                        |
3. If you don't want change some not required parameters, just remove them
- for example `https://theleername.github.io/LeerStreamChat?twitch_login=<twitch_channel_name>&size=20` will be after removing `https://theleername.github.io/LeerStreamChat?twitch_login=<twitch_channel_name>`
4. Now you have the cooliest chat :3

## TODO
- YouTube stream chat

## Special thanks
- node module [ComfyJS](https://github.com/instafluff/ComfyJS) by [instafluff](https://github.com/instafluff) <3