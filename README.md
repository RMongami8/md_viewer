# Notes Viewer (Obsidian風 zipビューアー)

Vaultをzipにしてブラウザで開くだけの静的ビューアー。ノートはリポジトリに含めない。

## 公開(GitHub Pages)
1. GitHubで新規リポジトリ(例: notes-viewer)を作成
2. このフォルダの index.html / manifest.json / sw.js / icon-*.png をアップロード(README.md は不要)
3. Settings → Pages → Branch: main / root → Save
4. https://<ユーザー名>.github.io/notes-viewer/ をiPadのSafariで開く
5. 共有ボタン → 「ホーム画面に追加」

## 使い方
1. PCでVaultフォルダをzip圧縮 → Google Driveに保存(上書き更新)
2. iPadで「zipを開く」→「ファイル」→ Google Drive → zipを選択
3. 2回目以降は前回のzipが自動で開く(更新したときだけ選び直す)

## 対応
[[wikilink]] / ![[画像|幅]] / コールアウト / 数式(KaTeX) / Mermaid / コードハイライト / タスク / ==ハイライト== / フロントマター / 被リンク / 全文検索 / ダークモード
