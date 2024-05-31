# wp-plugin-study
## 目的
- Mac localにおいてdocker環境上にWordPressプラグイン開発環境を構築するテスト

## 参考
- https://coosy.co.jp/blog/docker-environment/

## 手順

- 以下コマンドを実行
```
$ docker-compose up -d
(snip...)
[+] Running 5/5pmyadmin_ingrid                                                                       ✔ Network wp-plugin-study_default                                                                                                                           Created0.1s                                 ✔ Container mysql8                                                                                                                                          Started1.6s atch the detected host platform ✔ Container phpmyadmin_ingrid                                                                                                                               Started1.4s
 ✔ Container wordpress                                                                                                                                       Started1.4s
 ! phpmyadmin The requested image's platform (linux/amd64) does not match the detected host platform (linux/arm64/v8) and no specific platform was requested 0.0s

$ open http://localhost:10099 # PHPMyAdmin
$ open http://localhost:10090 # WordPress
```

## 夢
- イベントスケジュール
    - 参加登録
    - 運営要領の共有
    - Googleカレンダーへの追加
    - 自動的に記事のひな形を作成