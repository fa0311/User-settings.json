# %AppData%/Roaming/Code/User/

個人用なメモとか  
説明できない項目は基本的に消す  
大事な情報が流出する可能性が高いので Github で公開するのはオススメできない

この README を読んでも Vimmer には役に立たない

## User/settings.json

`editor.fontSize`  
アイコンサイズ  
デフォルトは 14 らしく 謎のこだわりで 13 にしている

`workbench.iconTheme`  
アイコンテーマ  
Material Icon Theme と vscode-icons の 2 強

`window.newWindowDimensions`  
新しいウィンドウの開き方  
`default`にしてる奴居ない

`editor.guides.bracketPairs`  
ブランケットに色を付ける  
昔は拡張機能でやってた

`editor.formatOnPaste`  
`editor.formatOnSave`  
`editor.formatOnType`  
フォーマットをするタイミング  
これらは余裕で全部オン

`git.confirmSync`  
同期の確認  
いちいち表示されるのは面倒

`editor.largeFileOptimizations`  
でかいファイル開いたときの最適化  
よくわからんけど false になってる(要検証)

`discord.*`  
Discord Presence 関連の日本語訳と設定  
デフォルト設定だと全てバレるから設定は必ずしたほうが良い  
`discord.removeRemoteRepository` は有効のほうが良いかも  
`discord.lowerDetailsEditing`を編集中の行数にすると AFK しているか否かを他人が判断できる

`trailing-spaces.*`  
半角スペースの色  
このプラグインは markdown の空白も赤く表示するので目立たない白色に変更  
エディタ上に赤色が表示されているよりも気持ちが落ち着く

`remote.SSH.remotePlatform`  
SSH プラットフォームの設定  
これオフにするかファイル分けてくれ  
Github に settings.json を公開するときは注意

`editor.defaultFormatter`  
デフォルトのフォーマッタ  
prettier 1 強  
beautify は前に使ってたけどメンテされなくなって切り替えた  
言語別のデフォルトフォーマッタは適当

`editor.rulers`  
エディタ上の指定の行数に線を入れる  
なんとなく入れてるけど従ったことがない

`redhat.telemetry.enabled`  
ログを送信する  
こういうのはたいていオフにしている

`terminal.integrated.enableMultiLinePasteWarning`  
複数行のターミナルへのコピペを警告する

`cSpell.enabled`  
スペルチェック  
ワークスペースごとに有効にしたほうが良い

`githubPullRequests.pullBranch`  
変更した時に Pull するか  
いちいち聞かれるのが面倒だから`never`

`dart.debugExternalPackageLibraries`  
`dart.debugSdkLibraries`  
外部のパッケージをデバックする  
実装を見に往くことがあるので有効

`dart.showInspectorNotificationsForWidgetErrors`  
Widget エラーを警告する  
邪魔だから無効

`vsicons.dontShowNewVersionMessage`  
アップデート通知  
邪魔だから無効

## User/keybindings.json

`pageup`  
`pagedown`  
ノパソ配列がクソで誤入力してしまうから無効  
Vimmer じゃないので十字キーで操作

## .vscode/settings.json

History ディレクトリがやたら重いしエラーが大量に出る  
静的解析は切ったほうが良い
