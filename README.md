# Lesson 35 Webアプリ v4

論理・表現II Lesson 35「無生物主語・名詞構文」の練習アプリです。

## 対応端末
- PC: Chrome / Edge / Safari / Firefox の新しい版
- iPad / iPhone: Safari
- Android: Chrome / Edge

画面幅に合わせて自動でレイアウトが変わります。タッチ操作とマウス・キーボード操作の両方に対応しています。

## 正解音
正解時にWeb Audio APIで短い「ピンポン♪」が鳴ります。外部音声ファイルは不要です。
画面上部の「🔊 音あり / 🔇 音なし」で切り替えられ、設定は端末内に保存されます。

※ ブラウザの仕様上、音はユーザーが画面を操作した後に再生されます。正解ボタンのクリック/タップ自体が操作になるため、通常はそのまま鳴ります。

## GitHub Pagesで公開
このフォルダの中身をリポジトリの一番上（root）にアップロードしてください。
`index.html` が Code 画面ですぐ見える状態にします。

Settings → Pages → Deploy from a branch → main → /(root) → Save

## ファイル
- index.html: アプリ本体
- manifest.webmanifest: PWA設定
- sw.js: オフラインキャッシュ
- icon-192.png / icon-512.png: アイコン
