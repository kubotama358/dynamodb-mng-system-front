# dynamodb-mng-system-front


# ■超初歩_動作確認
## トランスパイルを行い、client.min.jsを更新する。
```
webpack --mode development
```

## ブラウザでindex.htmlを開いて画面が表示されることを確認する。

# ■開発用サーバを起動
## 起動コマンドを実行
```
$ ./node_modules/webpack-dev-server/bin/webpack-dev-server.js --content-base src --mode development
```

## 動作確認
```$xslt
http://localhost:8080
```

