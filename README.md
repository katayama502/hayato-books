# 片山颯斗の本

片山颯斗の歩み・考え・noteと、5冊の著書を紹介する著者サイトです。

公開URL: https://katayama502.github.io/hayato-books/

## 構成

- `index.html` … サイト本体（HTML・CSS・JavaScriptを1ファイルに収録）
- `covers/` … 書籍の表紙、プロフィール画像、SNS共有用画像（`og.jpg`）
- `.github/workflows/pages.yml` … `main` に push すると GitHub Pages へ自動公開

## 更新のしかた

1. `index.html` を編集する
2. `main` ブランチに push する
3. 1〜2分で公開URLに反映される（進行状況は Actions タブで確認できます）

## メモ

- 価格・ランキングは2026年10月12日時点の表示です。変わったら `index.html` の該当箇所とフッターの日付を更新してください。
- 外部から読み込むのは Google Fonts のみです。Content-Security-Policy でそれ以外の読み込みと外部送信を止めています。
- 入力フォームやユーザー情報の保存はありません。
