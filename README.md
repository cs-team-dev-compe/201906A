## gitコマンド確認

フォルダ内でgitを使い始める
```terminal
git init
```

リモートリポジトリと接続する
```terminal
git remote add origin https://github.com/cs-team-dev-compe/201906A.git
```

今いるブランチを確認する
```terminal
git branch
```

ブランチを新たに作成して移動する
```terminal
git checkout -b (新しいブランチ名)
```

変更を確定する
```terminal
git add .
git commit -m "(コミットメッセージ：何を変更したか 例: "スティッキーヘッダーの実装")"
```

リモートリポジトリに変更を繁栄させる
```terminal
git push  origin (checkout -bで作ったブランチ名)
```
