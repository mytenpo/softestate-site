# 合同会社日本ソフトエステート ホームページ

GitHub Pages（Jekyll）で公開しているサイトです。文章や写真は、Pages CMS（https://app.pagescms.org）から編集できます。

## ファイルの場所

| 内容 | ファイル |
|---|---|
| 各ページの文章・写真 | `index.md`、`business.md`、`about.md` など（ページごとに1ファイル） |
| 会社名・住所・メニューなどの共通設定 | `_data/settings.yml` |
| 写真 | `assets/images/` |
| 動画 | `assets/video/` |
| デザイン（色・書体・配置） | `assets/css/style.css`、`_layouts/default.html`、`_includes/section.html` |
| 編集画面の設定 | `.pages.yml` |

## 独自ドメインへの切り替え

`_config.yml` の `url` を `https://www.softestate.co.jp`、`baseurl` を `""` に変更し、`CNAME` ファイル（中身は `www.softestate.co.jp`）を追加します。
