## gitコマンドリスト

| コマンド     | 　動作説明     | 一例 |
| :-------------: | :-------------: |:--:|
| git init       | gitローカルリポジトリとして初期化 | 空のフォルダで初期化しないとpullできない点に注意 |
| git remote add 変数名 URL | ローカルリポジトリを追加 | git remote add main https://github.gn5r/rd4c.git |
| git pull 変数名 ブランチ名 | 指定したブランチ名のリポジトリをpullする | git pull main master |
| git checkout -b ブランチ名 | 新規ブランチ作成 | git checkout -b gn5r |
| git add | push対象を追加(複数可) | git add README.md |
| git add . | 全てpush対象 | .(ドット)をつけるだけ |
| git commit -m "コメント" | 変更・追加などのコメントを付与 | git commit -m "initial commit" |
| git push 変数名 ブランチ名| リモートリポジトリへpush  | git push main master |
| git status | 変更・新規などの確認 | 赤文字でお知らせ |
|  |  |  |
