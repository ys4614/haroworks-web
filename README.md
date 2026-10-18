# HARO Works

HARO Works（ハロワークス）の公式ウェブサイトです。**このリポジトリが本番です。**

**公開サイト:** https://haroworks.com/

静的サイトのため、ビルド作業は不要です。`main` への push が GitHub Pages にそのまま反映されます。

## 構成

| ファイル | 説明 |
| --- | --- |
| `index.html` | サイト本体（トップページ） |
| `style.css` | スタイルシート |
| `assets/` | アプリアイコン |
| `CNAME` | 独自ドメイン設定（`haroworks.com`）— **削除・変更しないこと** |
| `app-ads.txt` | AdMob の広告主確認用（`pub-8513602258219243`）— **削除・変更しないこと** |
| `.nojekyll` | GitHub Pages の Jekyll 処理を無効化 |

`CNAME` と `app-ads.txt` は GitHub Pages のドメイン設定と AdMob 収益に直結しています。
`app-ads.txt` は `https://haroworks.com/app-ads.txt` で配信され続ける必要があります。

## 事業内容

- ソフトウェア開発
- モバイルアプリケーション開発
- AIツール開発
- Webサービス運営
- 自社アプリの配信・運営（App Store / Google Play）

## 自社アプリ

| アプリ | ストア |
| --- | --- |
| つぶトレ - AIスピーキングコーチ（TsubuTalk: AI Speaking Coach） | [App Store](https://apps.apple.com/jp/app/id6779087627) / [Google Play](https://play.google.com/store/apps/details?id=app.tsubutalk.mobile) |
| 連打名人 - Tap Champion | [App Store](https://apps.apple.com/jp/app/id6788312662) / [Google Play](https://play.google.com/store/apps/details?id=com.haroworks.tapchampion) |
| 残心スピリッツII（Zanshin Spirits II） | 2026-10-24 配信開始。公開後に [App Store](https://apps.apple.com/jp/app/id6822337942) / [Google Play](https://play.google.com/store/apps/details?id=com.haroworks.zanshinspirits2)（公開前は 404）。サイトのカードは「10/24 配信開始」表示で、公開日にストアのリンクへ差し替える |

## お問い合わせ

contact@haroworks.com

## 経緯

サイトの中身は以前 `haro-works-dev` リポジトリで管理し、`ys4614.github.io/haro-works-dev/` で公開していました。
一方このリポジトリは `haroworks.com` を Google Sites 版（`www.haroworks.com`）へ転送するだけのページでした。
現在は中身をこちらへ集約し、`haro-works-dev` は運用を終了しています。
