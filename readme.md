
# 概要

アドベンターカレンダーで紹介したWireMockのサンプルです。

## 前提

docker,docker-composeのインストールができていること。
curlコマンドがインストール(macなら多分大丈夫)

## 使用方法

cd docker
docker compose -f compose.yml up

## コマンド例

基本URL  
`curl http://localhost:8443/test/sample`

ファイルダウンロード例  
`curl http://localhost:8443/test/csv -o sample.zip`
