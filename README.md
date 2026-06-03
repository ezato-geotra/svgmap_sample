# SVGMap Sample

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