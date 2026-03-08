# Chainlit 技術書 補足資料

書籍のモノクロ紙面を補足するカラー図版・動画を掲載するGitHub Pagesサイトです。

## 構成

```
index.html          … 目次（親ページ）
pages/              … 子ページ（appendixN-xxx.html）
assets/videos/      … 動画ファイル（mp4）
style.css           … 共有CSS
```

## ローカル確認

```bash
python3 -m http.server 8080
```

## ページ追加手順

1. `pages/` 内の既存HTMLをコピー
2. `<title>` と本文を書き換え
3. 動画を `assets/videos/` に配置
4. `index.html` のリンク一覧に追記
