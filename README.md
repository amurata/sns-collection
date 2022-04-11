# Python で Twitter API を叩く

時間がないので雑い箇所多し

# 動作させる
`.env に APIキーを設定する`（必須）
ref. https://blog.palettecms.jp/article/20103 このへんかな？

## 起動 そして API を叩く
```sh
# docker-compose で pythonを立ち上げる
docker-compose up -d
# 立ち上がったら コンテナに入る
docker exec -it python3 /bin/bash
# python で twitter api を叩く(テスト)
python getTimeline.py
```

### issue化しましょ
- gitignore
- docker-compose.yml の volumes
- requirements.txt バージョン固定する
