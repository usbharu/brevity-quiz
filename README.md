# Brevity Quiz

米軍の共同刊行物「BREVITY」（2025年4月25日版）をもとにした、日本語の4択クイズです。日本語の説明は原資料の訳・要約で、難易度は本サイト独自の目安です。学習履歴は保存しません。回答後は、確認できた資料中の用例を原文と日本語訳で表示します。資料に用例が確認できない用語には例文を付けていません。

## ローカルで確認

ビルドや依存パッケージは不要です。このディレクトリで次を実行し、表示された URL をブラウザーで開いてください。

```sh
python3 -m http.server 8000
```

http://localhost:8000/

## Cloudflare Workers へのデプロイ

Cloudflare Workers Static Assets で公開しています。更新時は `cf` にログインしたうえで、次を実行してください。配信用の `public/` に5ファイルをコピーしてからデプロイします。

```sh
npm install
npm run deploy
```

独自ドメインは `cloudflare.config.ts` で指定しています。

## 出典

[BREVITY: Multi-Service Tactics, Techniques, and Procedures for Multi-Service Brevity Codes（2025年4月25日）](https://www.alssa.mil/Portals/9/Documents/mttps/brevity_2025.pdf)。各問題のリンクは資料に印字されたページに対応する PDF ページを開きます。
