# Github command

- リモート(github)の接続の確認

  - `git remote -v`

- リモートの追加
  - `git remote add origin <copy url from github>`

# 接続手順

## ローカル(自分のパソコン、git)の手順

- プロジェクト(フォルダを作る)
- プロジェクトを git に登録する - `git init`
- ローカル(git)でコミットを作成
  - `git add .`
  - `git commit -m "some comment"`

## リモート(クラウドサービス、github)との接続

- github にリポジトリ(保存場所)を作る
  - `create repository`ボタンを押して、作成
- github リポジトリ URL をコピー
- リポジトリ追加コマンドを実行
  - `git remote add origin <url>`
- リポジトリ接続を確認
  - `git remote -v`
