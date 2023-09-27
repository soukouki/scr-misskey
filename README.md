# scr-misskey
Tool to take screenshots, compress and post to misskey. I have separated what used to be part of https://github.com/soukouki/i3-settings. 

Dependencies: scrot, curl, jq, vscode, convert(ImageMagick)

Write the following variables in config.sh to run.

- misskey_token
- misskey_root(e.g. https://misskey.io/api)
- folder_name(used in drive of misskey. default is scr-misskey)
- workspace(default is /tmp/scr-misskey)

# scr-misskey
スクリーンショットを取り、圧縮し、misskeyに投稿します。 https://github.com/soukouki/i3-settings の一部となっていたコードを切り出しました。

scrot, curl, jq, vscode, convert(ImageMagick) に依存しています。

実行には以下の変数をconfig.shで定義してください。

- misskey_token
- misskey_root(例えば、https://misskey.io/api)
- folder_name(misskeyのドライブ内で使われます。デフォルトはscr-misskey)
- workspace(デフォルトは~/tmp/scr-misskey)
