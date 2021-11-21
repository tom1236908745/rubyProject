# rubyProject

## フォルダの説明

### utills -> 文法など、よく使うもののまとめ

## Ruby on Railsに関して

## Ruby on Railsで使うコマンド群

## プロジェクト作成コマンド
```
rails new new_app
```
サーバー起動
```
rails server
```

トップページ作成コマンド
```
rails generate controller home top
```

## ページ作成に必要な３つの要素

- ビュー
- コントローラー
- ルーティング


### ビュー
viewsフォルダに配置される。

### コントローラ
ビューはコントローラを介して表示される。
( app/controllers/home_controller.rb )

### ルーティング
ブラウザとコントローラを繋ぐのがルーティング
( app/config/routes.rb )

コントローラを使用しアクションを発火させるための文法
```
get "URL" => "コントローラー名#アクション名

```

ルーティング　→　コントローラ　→ ビュー
