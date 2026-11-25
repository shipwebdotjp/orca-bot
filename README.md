# Orca Bot — GitHub Pages

Google OAuth 同意画面の「アプリのホームページ」および「プライバシーポリシー」URL 用の静的サイトです。

## URL

- ホーム: https://shipwebdotjp.github.io/orca-bot/
- プライバシーポリシー: https://shipwebdotjp.github.io/orca-bot/privacy/

## 構成

```
index.html          ホーム（アプリの説明・Google API 利用について）
privacy/index.html  プライバシーポリシー（日本語＋英語サマリ）
style.css           共通スタイル
```

ビルド不要の静的 HTML です。`main` ブランチのルートをそのまま配信します。

## 更新方法

```sh
git add .
git commit -m "Update site"
git push
```

反映まで 1 分ほどかかることがあります。

## メモ

- アプリの内容や外部送信先（LLM API など）が変わったら、`privacy/index.html` の「3. 外部サービスへの送信」を必ず更新する。
- 文面は法的助言ではありません。公開範囲を広げる場合は必要に応じて専門家に確認する。
