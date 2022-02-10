# roadmap-intermediate
ロードマップ中級編

環境構築がうまくできない、もしくは.  
環境構築のやり方は分かるので手間を省きたい方は以下の手順で環境を作成してください

初回起動
```
cd roadmap-intermediate
```

```
make init
```

2回目以降は
```
docker-compose up -d
```
でコンテナを立ち上げてください


tailwindcssでホットリロードしていく場合は下記コマンドを使用してください
```
make watch
```
