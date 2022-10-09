# 初期化コマンド

- `git init`

# よく使うコマンド

- `git status`
- `git add .`
- `git commit -m "some comment"`

# 説明

- git

  - バージョン管理

- 初期化、有効化される

  - `git init`

- 場所

  - ワーキングエリア
    - すべてのファイルはここにある
    - 赤色のファイルがワーキングエリア内のファイル
  - ステージエリア
    - セーブしたいファイルだけ登録する場所
    - 緑色のファイルがステージエリアのファイル
    - コミットコマンドを実行すると、ここにあるファイルはすべてセーブされる
  - セーブ
    - `git commit -m "sample comment"`

- ステータス確認

  - git status

- 追加

  - git add . / 全部追加
  - git add ファイル名

- セーブ

  - git commit -m "コミットメッセージ"

- git graph
  - 可視化ツール
