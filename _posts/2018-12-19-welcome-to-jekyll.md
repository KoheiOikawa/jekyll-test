---
layout: default
title:  "Jekyllで始めるブログ"
date:   2018-12-19 19:00:00 +0900
categories:
- basis
---
# ローカルで動かしてみる

## cloneする

適当なディレクトリにcloneします。

その後、そのディレクトリで以下のコマンドを実行:

```sh
bundle --path vendor/bundle
bundle exec jekyll serve
```

すると、ターミナルが以下のような出力で止まるので:

```
Server address: http://127.0.0.1:4000/
Server running... press ctrl-c to stop.
```

Webブラウザで[http://127.0.0.1:4000/jekyll-test/](http://127.0.0.1:4000/jekyll-test/)にアクセスすると、ローカル環境でjekyllがホストするブログを閲覧できます。
