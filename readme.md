＃ 概要

アドベンターカレンダーで紹介したWireMockのサンプルです。

## 前提
docker,docker-composeのインストールができていること。
curlコマンドがインストール(macなら多分大丈夫)

## 使用方法
docker compose -f compose.yml up

## サンプル

curl http://localhost:8443

サンプルURL
curl http://localhost:8443/test/hello

curl http://localhost:8443/test/csv -o sample.zip
## マップ一覧

curl http://localhost:8443/__admin/mappings