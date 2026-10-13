# 大丸 LINE注文デモ（LIFF対応）

## ファイル配置
- `/index.html` : 本番用LIFF ID（一般ユーザー向けの画面テスト）
- `/dev/index.html` : 開発用LIFF ID（管理者・テスター向け）

GitHub Pagesに上記の相対パスどおりに配置する。

## GitHub Pages URL
- 本番用エンドポイント: https://imaijin-1224.github.io/daimaru-line-demo/
- 開発用エンドポイント: https://imaijin-1224.github.io/daimaru-line-demo/dev/

## LINE Developers 設定
- 本番用エンドポイントURLに本番用URLを指定
- 開発用エンドポイントURLに開発用URLを指定
- 審査用はまだ変更しない

## LIFF URL
- 本番用: https://miniapp.line.me/2011985171-wZHFKWf8
- 開発用: https://miniapp.line.me/2011985169-7Rewucm4

## 注意
- これは注文入力画面のデモであり、注文受付・送信・DB保存処理は実装していない。
- 商品名・価格・セット構成は仮データ。
- GitHub Pagesは公開サイトのため、実際のお客様の氏名や電話番号を入力しない。
- 店舗の実運用・商用決済・受注受付には、別途バックエンド/個人情報保護等が必要。
- GitHubリポジトリを開発用としてPublicで公開していることに注意。
