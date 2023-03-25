# scr-misskey
Tool to take screenshots, compress and post to misskey. I have separated what used to be part of https://github.com/soukouki/i3-settings. 

Dependencies: scrot, curl, jq, vim, feh, convert(ImageMagick)

Write the following variables in config.sh to run.

- misskey_token
- misskey_root(eg. https://misskey.io/api)
- folder_name(eg. screenshot)
- terminal_emulator_start_command(eg. wezterm start)
