# SVGMap Sample

## GitHub Pages
GitHub Actions で Docker の起動確認を行った後、`index.html` を GitHub Pages に公開します。

### GitHub 側の設定
1. GitHub リポジトリの `Settings` > `Pages` を開く
2. `Build and deployment` の `Source` を `GitHub Actions` に変更する
3. `main` ブランチに push する

公開 URL は Actions の `deploy-pages` job、または `Settings` > `Pages` で確認できます。

## Docker コマンド
### 起動
```bash
docker compose up -d --build
```
### 停止
```bash
docker compose down
```

## Proxy 動いてるか確認する方法
`Docker` を起動した状態で下記URLにアクセス

[Example Domain](http://localhost:8080/corsaw/proxy.php?csurl=https://example.com/)

画面が正常に表示されればOK
