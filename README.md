# 教材
- 以下の”Rails をはじめよう”を実行したリポジトリです

URL: [https://railsguides.jp/getting_started.html](https://railsguides.jp/getting_started.html)

# バージョン
- 以下のバージョンで動作を行っています

```
$ sqlite3 --version
3.32.3
$ ruby -v
ruby 2.7.1
$ rails --version
Rails 6.0.3.4
```

# 注意
## アプリケーションのビルド時
- `rails new blog`をする際は以下のコマンドを実行します

```
rails new blog --skip-javascript --skip-yarn
```

## 削除(destroy)アクションは実行できない
- 上記で`--skip-javascript --skip-yarn`をしているため、`rails-ujs`を用いるdestroyメソッドの実行はできません
