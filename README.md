# HAYATO WORKS｜片山颯斗の本

片山颯斗の歩み・考え・noteと、5冊の著書を紹介する著者サイトです。

公開URL: https://hkdesign.site/

## 構成

- `index.html` … サイト本体（HTML・CSS・JavaScriptを1ファイルに収録）
- `covers/` … 書籍の表紙、プロフィール画像、SNS共有用画像（`og.jpg`、1200×630）
- `favicon.png` / `apple-touch-icon.png` … ブラウザとスマホのホーム画面用アイコン
- `robots.txt` / `sitemap.xml` … 検索エンジン向けの案内
- `CNAME` … 独自ドメイン（hkdesign.site）の設定
- `.github/workflows/pages.yml` … `main` に push すると GitHub Pages へ自動公開

## 更新のしかた

1. `index.html` を編集する
2. `main` ブランチに push する
3. 1〜2分で公開URLに反映される（進行状況は Actions タブで確認できます）

本を追加・変更したときは、次の3か所も合わせて更新してください。

- `index.html` 内の構造化データ（`<script type="application/ld+json">`）の Book 情報
- `index.html` 内の JavaScript の `BOOKS`（1冊診断と画面下の購入バーで使用）
- `sitemap.xml` の `lastmod`

## SEOの設定

- タイトル、説明文、正規URL（canonical）、OGP・Xカード
- 構造化データ（WebSite / Person / Book ×5、各本にKindle版・ペーパーバックの価格とISBN）
- 画像の幅・高さ指定（表示のずれ防止）、プロフィール画像の優先読み込み

公開後は Google Search Console に `https://hkdesign.site/` を登録し、`sitemap.xml` を送信すると検索結果への反映が早まります。

## メモ

- 価格・ランキングは2026年10月12日時点の表示です。変わったら `index.html` の該当箇所とフッターの日付を更新してください。
- 外部から読み込むのは Google Fonts のみです。Content-Security-Policy でそれ以外の読み込みと外部送信を止めています。
- 入力フォームやユーザー情報の保存はありません。
