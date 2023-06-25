# GITの勉強

- git add コマンドで、リポジトリに変更情報を追加する
　- このことをステージリングと言う
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる
  - git push だけで今いるブランチにpushできる
  - git push origin ブランチ名 にすると、ブランチを指定してpushできる

- 開発スタート時
  - GitHubでSSHキーをコピー
  - ターミナルを開いて、リポジトリを入れたいディレクトリに移動（cd フォルダ名）
  - git clone コピーした文字列

- よく使うコマンド
  - git add .
  - git commit -m "○○を変更した"
  - git push (origin ブランチ名)
