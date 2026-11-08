# 救命ワードウルフ（独自サイト版）

`index.html` と `words.js` の2ファイルだけで動きます（サーバー・AI不要）。

## お題の追加
`words.js` の最後の `];` の前に、次の形で1組ずつ足します。
`["語1","語2","語1の解説","語2の解説"],`
解説の中で半角の `"` は使わないでください。

## フォームの設定
`index.html` の冒頭にある `CFG` に、GoogleフォームなどのURLを貼ります。
- `formSubmit`：お題の提供用（語1、語2、解説案）
- `formReport`：解説の誤り報告用（お題の語、誤りの内容）
空欄の間は、該当のボタンは表示されません。

## 公開方法（無料）
- GitHub Pages：リポジトリに2ファイルを置き、Settings > Pages で公開
- Cloudflare Pages：2ファイルを入れたフォルダをアップロード
`index.html` と `words.js` は同じ場所に置いてください。

## 注意
解説は下書きです。公開前に教科書・ガイドラインで確認してください。
「学習の補助です」の注記は結果画面に表示されます。

## 公開時のSEO設定
- 正規URLは `https://watap999.github.io/paramedic-wolf/` に設定済みです（`index.html`・`robots.txt`・`sitemap.xml`）。URLを変える場合は、この3か所を置換してください。
- 公開後、Google Search Console にサイトを登録し、`sitemap.xml` を送信してください。
- SNS共有の画像は `og-image.png`（QRコード入り・1200×630）です。URLを変えた場合は、QRコードも作り直してください。
- 同梱：`favicon.svg`、`favicon-32.png`、`apple-touch-icon.png`、`manifest.webmanifest`、`icon-192.png`、`icon-512.png`
